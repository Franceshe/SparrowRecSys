tensorflow git:(master) python3 WideNDeep.py 

Downloading data from file:///Users/siyunhe/project/Summer2020/SomerCloud/Algorithm/recommendation-system/Wide-deep-Learning/zhe_wang/SparrowRecSys/src/main/resources/webroot/sampledata/modelSamples.csv
15982592/15978252 [==============================] - 0s 0us/step
2020-11-29 21:52:42.316213: I tensorflow/core/platform/cpu_feature_guard.cc:142] This TensorFlow binary is optimized with oneAPI Deep Neural Network Library (oneDNN)to use the following CPU instructions in performance-critical operations:  AVX2 FMA
To enable them in other operations, rebuild TensorFlow with the appropriate compiler flags.
2020-11-29 21:52:42.337613: I tensorflow/compiler/xla/service/service.cc:168] XLA service 0x7fe694eabd40 initialized for platform Host (this does not guarantee that XLA will be used). Devices:
2020-11-29 21:52:42.337634: I tensorflow/compiler/xla/service/service.cc:176]   StreamExecutor device (0): Host, Default Version
<PrefetchDataset shapes: (OrderedDict([(movieId, (None,)), (userId, (None,)), (rating, (None,)), (timestamp, (None,)), (releaseYear, (None,)), (movieGenre1, (None,)), (movieGenre2, (None,)), (movieGenre3, (None,)), (movieRatingCount, (None,)), (movieAvgRating, (None,)), (movieRatingStddev, (None,)), (userRatedMovie1, (None,)), (userRatedMovie2, (None,)), (userRatedMovie3, (None,)), (userRatedMovie4, (None,)), (userRatedMovie5, (None,)), (userRatingCount, (None,)), (userAvgReleaseYear, (None,)), (userReleaseYearStddev, (None,)), (userAvgRating, (None,)), (userRatingStddev, (None,)), (userGenre1, (None,)), (userGenre2, (None,)), (userGenre3, (None,)), (userGenre4, (None,)), (userGenre5, (None,))]), (None,)), types: (OrderedDict([(movieId, tf.int32), (userId, tf.int32), (rating, tf.float32), (timestamp, tf.int32), (releaseYear, tf.int32), (movieGenre1, tf.string), (movieGenre2, tf.string), (movieGenre3, tf.string), (movieRatingCount, tf.int32), (movieAvgRating, tf.float32), (movieRatingStddev, tf.float32), (userRatedMovie1, tf.int32), (userRatedMovie2, tf.int32), (userRatedMovie3, tf.int32), (userRatedMovie4, tf.int32), (userRatedMovie5, tf.int32), (userRatingCount, tf.int32), (userAvgReleaseYear, tf.int32), (userReleaseYearStddev, tf.float32), (userAvgRating, tf.float32), (userRatingStddev, tf.float32), (userGenre1, tf.string), (userGenre2, tf.string), (userGenre3, tf.string), (userGenre4, tf.string), (userGenre5, tf.string)]), tf.int32)>
Epoch 1/5
/usr/local/lib/python3.7/site-packages/tensorflow/python/keras/engine/functional.py:543: UserWarning: Input dict contained keys ['rating', 'timestamp', 'userRatedMovie2', 'userRatedMovie3', 'userRatedMovie4', 'userRatedMovie5', 'userAvgReleaseYear', 'userReleaseYearStddev'] which did not match any model input. They will be ignored by the model.
  [n for n in tensors.keys() if n not in ref_input_names])
  8232/8232 [==============================] - 43s 5ms/step - loss: 0.7357 - accuracy: 0.6142
  Epoch 2/5
  8232/8232 [==============================] - 47s 6ms/step - loss: 0.5904 - accuracy: 0.6933
  Epoch 3/5
  8232/8232 [==============================] - 50s 6ms/step - loss: 0.5426 - accuracy: 0.7268
  Epoch 4/5
  8232/8232 [==============================] - 49s 6ms/step - loss: 0.5084 - accuracy: 0.7520
  Epoch 5/5
  8232/8232 [==============================] - 49s 6ms/step - loss: 0.4882 - accuracy: 0.7645
  1000/1000 [==============================] - 2s 2ms/step - loss: 0.5293 - accuracy: 0.7365
  
  
  Test Loss 0.5293036103248596, Test Accuracy 0.7365000247955322
  Predicted good rating: 37.45%  | Actual rating label:  Good Rating
  Predicted good rating: 75.50%  | Actual rating label:  Good Rating
  Predicted good rating: 85.58%  | Actual rating label:  Bad Rating
  Predicted good rating: 26.70%  | Actual rating label:  Good Rating
  Predicted good rating: 72.01%  | Actual rating label:  Good Rating
  Predicted good rating: 31.14%  | Actual rating label:  Good Rating
  Predicted good rating: 44.78%  | Actual rating label:  Good Rating
  Predicted good rating: 64.43%  | Actual rating label:  Good Rating
  Predicted good rating: 16.22%  | Actual rating label:  Good Rating
  Predicted good rating: 77.40%  | Actual rating label:  Bad Rating
  Predicted good rating: 47.56%  | Actual rating label:  Good Rating
  Predicted good rating: 14.52%  | Actual rating label:  Bad Rating~
