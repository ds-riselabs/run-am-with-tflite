# run-am-with-tflite

### Run-Am News Verification App on Android using TensorFlow Lite

#### News Verification text classifier model built for Run-Am and deployed on an Android app using TensorFlow Lite.

##### Steps:

1. Clone the repository on your local machine.

2. Sign in to your Google account and upload the `Run-Am with Tflite.ipynb` notebook on Colab.

3. Run the notebook cells one-by-one by following the instructions.

4. Once the TF Lite model is downloaded, copy the `.tflite` model file inside `run-am-with-tflite/lib_task_api/src/main/assets` directory.

5. Open the project in Android Studio and let it build itself for some time.

6. Open TextClassificationClient.java file under `lib_task_api` and edit Line 31 by replacing `<your_model.tflite>` with the name of your actual TF Lite model.

7. Build the project and install it on your phone.

#### Note: To build this project, request for the training dataset.
