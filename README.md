# yoga_pose_detection-
Project: Yoga Pose Correction using MediaPipe
Project Overview
The Yoga Pose Detection project is designed to identify and evaluate yoga poses using computer vision techniques. This system captures body landmarks, calculates angles between key joints, and provides feedback to guide users in correcting their posture. The primary objective is to assist users in performing yoga poses accurately and improving their form.

Key Components
Pose Detection Framework:

Framework Used: MediaPipe Pose Estimation library, which provides real-time human body pose tracking by capturing key landmarks.
Key Landmarks: Detection of 33 body points such as elbows, knees, shoulders, etc., enabling detailed analysis.
Data Preprocessing:

The dataset includes images and their corresponding labels. The data was preprocessed to:
Extract coordinates of key landmarks.
Normalize and standardize the data for consistent input to the pose detection algorithm.
Pose Correction Logic:

Calculated angles between specific joints using trigonometric formulas.
Implemented logic to compare detected angles with ideal angles for each pose.
Feedback is generated, e.g., "Adjust your Left Elbow position! Current angle: 180.00°".
Evaluation and Accuracy:

The accuracy of pose detection is 50% (0.5), meaning the system can identify correct poses with moderate reliability.
The results are derived by comparing predicted poses with ground truth data.
Visualization:

Pose landmarks and feedback are displayed visually on the user's live feed or input image for real-time guidance.
Tools Used:

Programming Language: Python
Libraries: MediaPipe, NumPy, Pandas, OpenCV
Platform: Google Colab for model development and testing.

