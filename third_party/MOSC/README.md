# MOSC Model Collection

This repository contains several test models for robotics research and development. Below is an explanation of each model and their recommended usage:

## Model Descriptions

- **MOSC_0516.urdf** & **MOSC.xml**  
  These are the first version models. All joints are movable, and the default pose is a T-pose.

- **MOSC_up_hand**  
  This variant has the robot's hands raised.

- **MOSC_OL**  
  "OL" stands for "Only Leg". In this model, all upper body joints are locked, allowing only the legs to move.

- **MOSC_OL_up_hand.xml**  
  This is a recommended model. It is similar to MOSC_OL but with the robot's hands raised. All upper body joints are locked.

- **MOSC_0516_offset_up_hand.urdf**  
  This is another recommended model. "Offset" means that the leg joints have initial values, so the default pose is a knee-bent standing posture. All upper body joints are locked, and the hands are raised.

## Recommendations

For most use cases, we recommend using either **MOSC_OL_up_hand.xml** or **MOSC_0516_offset_up_hand.urdf**, as they provide a practical starting pose with locked upper body joints and raised hands.



    name_list = [
        'b_Lh', 'b_Ls', 
        'b_Rh', 'b_Rs', 'b_n',
        'Lh_Ll', 'Ls_La', 
        'Rh_Rl', 'Rs_Ra', 'n_h',
        'Ll_Ll1', 'La_Lh', 
        'Rl_Rl1', 'Ra_Rh', 
        'Ll1_Ll2', 'Rl1_Rl2', 
        'Ll2_La', 'Rl2_Ra', 
        'La_Lf', 'Ra_Rf'
    ]

    full_good_name_list = [
          'left_hip_pitch', 'left_shoulder_pitch', 
          'right_hip_pitch', 'right_shoulder_pitch', 'neck_yaw',
          'left_hip_roll', 'left_shoulder_roll', 
          'right_hip_roll', 'right_shoulder_roll', 'neck_pitch',
          'left_hip_yaw', 'left_elbow', 
          'right_hip_yaw', 'right_elbow',
          'left_knee', 'right_knee', 
          'left_ankle_pitch', 'right_ankle_pitch',
          'left_ankle_roll', 'right_ankle_roll'
          ]
