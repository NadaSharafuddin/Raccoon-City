This UiPath sequence is designed to detect the presence of emojis in a given text input using a regular expression. 
If an emoji is detected, the workflow throws a custom exception to prevent further processing. 
This is particularly useful in scenarios where emoji-free text is required, such as formal data entry, logging, or communication with systems that do not support Unicode emoji characters.
The detection is performed using a regex. The regex pattern captures a wide range of Unicode emoji characters, including symbols, pictographs, and supplementary multilingual plane emojis.
