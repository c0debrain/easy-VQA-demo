# easy-VQA-demo

A demo of a [Keras](https://keras.io/) model trained on the [easy-VQA](https://github.com/vzhou842/easy-VQA) (Easy Visual Question Answering) dataset.

See the demo live at https://easy-vqa-demo.victorzhou.com.

## About the Demo

The demo web app was made using [create-react-app](https://github.com/facebook/create-react-app).

The demo model uses [TensorFlow.js](https://www.tensorflow.org/js) to run predictions using pre-trained weights directly in the browser.

The pre-trained Keras model is available at `public/model.h5`. It was converted to `public/model.json` using the official [TensorFlow.js converter](https://www.tensorflow.org/js/guide/conversion).
