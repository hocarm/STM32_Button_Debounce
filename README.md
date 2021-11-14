# STM32 Continuous Integration example 
Click here to see the latest build result and artifact on CircleCI - [![CircleCI](https://circleci.com/gh/hocarm/STM32_Button_Debounce/tree/master.svg?style=svg)](https://circleci.com/gh/hocarm/STM32_Button_Debounce/tree/master)

## What's in this sample

1. We used an mBed STM32 deboucer project to demonstrate how to test a button with a debouncer. The code turns on an LED every time the button is pressed.
2. We then created a Docker container with the toolchain installed.
3. We create a Jumper test script that presses the button multiple times, but thanks to the debouncer it should only count as one.
4. Next, we configured CircleCI and TravisCI to build and run our testsour project every time we push new code to GitHub.
