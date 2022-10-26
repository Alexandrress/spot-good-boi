<!--
Copyright (c) 2022 Boston Dynamics, Inc.  All rights reserved.

Downloading, reproducing, distributing or otherwise using the SDK Software
is subject to the terms and conditions of the Boston Dynamics Software
Development Kit License (20191101-BDSDK-SL).
-->

# Spot Good Boi

Simple program to simulate a dog waiting to be pet with Spot.

![ezgif com-gif-maker](https://user-images.githubusercontent.com/11575580/198077580-7fc71404-c5d3-42f3-a965-1fa8b4be4994.gif)

## Understanding Spot Programming

For your best learning experience, please use the [Quickstart Guide](../../../docs/python/quickstart.md) found in the SDK's docs/python directory. That will help you get your Python programming environment set up properly. Then, specifically for Hello Spot, you should look at the [Understanding Spot Programming](../../../docs/python/understanding_spot_programming.md) file in the same directory. This document walks you through all the commands found in this example!

## Setup Dependencies

See the requirements.txt file for a list of python dependencies which can be installed with pip using the command:

```
python3 -m pip install -r requirements.txt
```

## Common Problems

1. Remember, you will need to launch a software e-stop separately. The E-Stop programming example is [here](../estop/README.md).
2. Make sure the Motor Enable button on the Spot rear panel is depressed.
3. If you have a problem with Pillow/PIL, did you run the pip install with the requirements.txt as described above?
4. Make sure Spot is sitting upright, with the battery compartment on the side closest the floor.

## Run the Example

To run the example:

```
python3 spot_good_boi.py ROBOT_IP
```
