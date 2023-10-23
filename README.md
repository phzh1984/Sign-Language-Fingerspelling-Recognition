# Sign-Language-Fingerspelling-Recognition

Description 

This repository contains a model designed for detecting and translating Sign Language fingerspelling into text. The model has been trained on a comprehensive dataset. This dataset comprises over three million fingerspelled characters, recorded by more than 100 Deaf signers using the selfie camera on a smartphone under various background and lighting conditions.

The objective of this project is to advance the field of sign language recognition, contributing to the accessibility of AI for the Deaf and Hard of Hearing community.

Context

In today's world, voice-enabled assistants offer a wide range of useful features, from automated speech recognition (ASR) to machine translation. However, these technologies often remain inaccessible to the more than 70 million Deaf individuals worldwide and the 1.5+ billion people affected by hearing loss. Fingerspelling, which uses hand shapes to represent individual letters, plays a crucial role in sign language, particularly for conveying names, addresses, phone numbers, and other information typically entered on mobile devices. Notably, many Deaf smartphone users can fingerspell words more rapidly than they can type on virtual keyboards. Despite this, sign language recognition for text entry lags behind voice-to-text and gesture-based typing, mainly due to the lack of robust datasets. 

This project aligns with Google's mission to make information universally accessible and useful, and it is supported by Google's AI principles, which aim to create products that empower people, benefit current and future generations, and serve the common good. 

This work could help provide Deaf and Hard of Hearing users with the option to fingerspell words instead of using a keyboard. Beyond convenient text entry, there is the potential for an app that can translate this input into spoken language using sign language-to-speech technology, facilitating smoother communication with hearing non-signers.


Dataset Files

[train/supplemental_metadata].csv:

path: Path to the landmark file.

file_id: A unique identifier for the data file.

participant_id: A unique identifier for the data contributor.

sequence_id: A unique identifier for the landmark sequence.

phrase: Labels for the landmark sequence, which may include randomly generated addresses, phone numbers, and URLs.

character_to_prediction_index.json: JSON file for mapping characters to prediction indices.

[train/supplemental]_landmarks/: The landmark data extracted from raw videos using the MediaPipe holistic model. It includes spatial coordinate columns (x, y, z) for various landmark types ('face', 'left_hand', 'pose', 'right_hand').

Please note that the dataset is designed to support the Deaf and Hard of Hearing community and should not be used for identity recognition or unique biometric identification.
