# AI-Model-with-Flask
Flask-Based Handwritten Digit Recognition API Overview This Flask application serves as an API for predicting handwritten digits using a pre-trained deep learning model. The app accepts an image (in base64 format), processes it, and returns the predicted digit. It also provides a simple frontend (index.html) for users to interact with the model.
Key Features
✅ Flask Backend: Handles HTTP requests for digit recognition.
✅ TensorFlow Model Loading: Loads a trained neural network model (digit_model.keras or digit_model.h5).
✅ Image Processing: Converts input images to grayscale, resizes them to 28x28 pixels, and normalizes pixel values.
✅ REST API Endpoint (/predict): Accepts image data, processes it, and returns a predicted digit.
✅ CORS Support: Allows cross-origin requests for frontend integration
