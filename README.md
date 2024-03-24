# keyLogger

# Key Features:

Keystroke Logging: Records every key pressed on the keyboard.
Logging Module: Uses the logging module for structured output.
pynput Library: Employs the external pynput library for keyboard event handling.
Functionality:

# Logging Setup:

Configures logging to write messages to a file named "keylog.txt".
Sets the logging level to DEBUG for detailed output.
Uses the format "%(asctime)s - %(message)s" for timestamps and messages.

# Key Press Listener:

Defines the on_press function to handle key press events.
Logs the pressed key's string representation using logging.info.

# Key Listener Activation:

Creates a Listener object linked to the on_press function.
Uses the with statement to ensure proper resource management.
Calls listener.join() to start the listener and keep it running indefinitely!

#Ethical Concerns and Responsible Use:

Obtain explicit consent before using this code on others' devices.
Restrict its use to educational or research purposes in controlled settings.
Refrain from using it for malicious activities or unauthorized surveillance.
Prioritize transparency and respect for privacy when handling sensitive information.
