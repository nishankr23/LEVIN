# LEVIN (Learning Enhanced Visualization Integrated with NLP)

  LEVIN is a Speech-to-Image Synthesis Model designed to simplify and enhance the teaching process. It works by taking speech inputs, converting them into text, and then using that text to fetch relevant images from a dataset. This makes it possible to automate the creation of visual aids based on spoken instructions, making learning more interactive and engaging. LEVIN aims to bridge the gap between verbal instructions and visual learning, offering a practical tool for educators and learners alike.

Libraries:
- tkinter: Used for the GUI framework in app.py.
- PIL (from Pillow): Used for image manipulation (Image and ImageTk in app.py).
- subprocess: Standard library module for executing shell commands.
- os: Standard library module for file and path operations.
- spacy: NLP library used extensively across all scripts.
    Requires the en_core_web_sm language model (spacy download en_core_web_sm).
- speech_recognition: For speech-to-text conversion in app.py.
- threading: Standard library module for managing threads.
- sounddevice: For audio input/output in app.py.
- soundfile: To handle audio file operations.
- queue: Standard library module for managing audio buffers.
