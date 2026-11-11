# Health Care Chatbot

A small Tkinter chatbot demo based on the FAQ patterns in `intents.json`.

## Run on Windows

1. Install Python 3.
2. Double-click `Run MedBot.bat`, or open a terminal in this folder and run:

   ```powershell
   python gui.py
   ```

The GUI uses only Python's standard library. It matches input against the bundled intent patterns; it does not understand conversational follow-ups such as “yes”.

`chatbot_py.py` is a separate model-backed console version and requires TensorFlow, NumPy, and NLTK. The Tkinter GUI does not load that model.

## Medical disclaimer

This is an educational demo. Its preset responses are not medical advice and must not be used to diagnose or treat a health condition. For medical concerns, contact a qualified health professional.

## License

See [LICENSE](LICENSE).
