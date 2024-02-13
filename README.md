# Bowling-Analyzer

<p align="center">
  <img src="https://github.com/MOSHIIUR/Bowling-Analyzer/blob/main/Data/readme/Bowlingaction.gif" alt="GIF" />
</p>

<p align="center">
  <img src="https://github.com/MOSHIIUR/Bowling-Analyzer/blob/main/Data/readme/left_knee.png" alt="plot 1" width="400"/>
  <img src="https://github.com/MOSHIIUR/Bowling-Analyzer/blob/main/Data/readme/right_knee.png" alt="plot 2" width="400"/>
</p>


## Usage

1. Clone this repository to your local machine:

2. Set the path accordingly to the path where your bowling action data is located.

3. Choose the player(s) you want to analyze by modifying the `players` list.

4. Specify the `bowling_action` and `movement` variables according to your analysis requirements.

5. Define the `keypoints` list to specify the keypoints you want to analyze from given landmarks below.

6. Run the code cell containing the CricketAnalyzer instantiation.

## Example

```python
root_folder = r'G:\DL_enigma\Bowling-Analyzer\Data'
players = ['Mitchell Starc']

bowling_action = 'Front'  # Choose from: [SideOn][Rear][Front] angle
movement = 'Left Knee Angle'  # Handl, Truck, etc. Choose the movement you want to analyze more 
keypoints = ['x_23', 'y_23', 'x_25', 'y_25', 'x_27', 'y_27']  # Specify the keypoints

player = CricketAnalyzer(root_folder, players, bowling_action, movement, keypoints)

```

## keypoints Calculation and the complete dataset will be available soon.

