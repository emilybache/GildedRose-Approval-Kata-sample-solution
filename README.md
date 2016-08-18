Gilded Rose Approval Kata with TextTest - sample solution
=========================================================

This repo has a sample solution texttest test suite for this kata.

Viewing and Running the texttests
---------------------------------

(assuming you already have texttest installed, see http://texttest.org)

You will need to point out the location of your clone of the code, so that texttest can find it. In your personal texttest config file $HOME/.texttest/config, include this:

    [checkout_location]
    gilded-rose:/home/demo/workspace/GildedRose-Approval-Kata-sample-solution/java

You will also need to run 'mvn install' in this project

    $ cd java
    $ mvn install

Then you can open the texttest GUI like this:

    texttest -a gr
