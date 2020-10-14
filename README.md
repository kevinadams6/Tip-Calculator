# Tip Calculator 

## *Kevin Adams*

**Tippy** computes the tip and total amount for a bill. The app uses the base amount and tip percentage to calculate the amount owed, and it also describes the quality of service based on the tip.

Time spent: **5** hours spent in total

## Functionality 

The following **required** functionality is completed:

* [X] User can enter in a bill amount (total amount to tip on)
* [X] User can enter a tip percentage (what % the user wants to tip).
* [X] The tip and total amount are updated immediately when any of the inputs changes.
* [X] The user sees a label or color update based on the tip amount. 

The following **extensions** are implemented:

* [X] Custom colors palette selected
* [X] Emojis in tip description
* [X] User can select to split total amount between up to 15 people

## Video Walkthrough

Here's a walkthrough of **Tippy**:

<img src='https://i.imgur.com/pGnccm9.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

## Notes

One challenge I faced while creating this app was updating the per person amount correctly. Since a seek bar's progress can go down to zero, I had to make sure I was not dividing by zero when calculating the per person amount. An easy fix was to limit the seek bar's max to 14 and then always add 1 to its value when calculating the per person amount.

## License

    Copyright 2020 Kevin Adams

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
