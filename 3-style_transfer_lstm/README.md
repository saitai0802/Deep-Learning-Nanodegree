## Intro.
In this demo, I will show you how to use a pre-trained model(vgg16) to implement a Deep Learning network to learn from a  image and apply the style a photo that I took in JP by using Transfer Learning.

## Dependencies

run `pip install -r requirements.txt` to install the necessary dependencies


## Usage

If it doesn't exist, create a file called ~/.keras/keras.json and make sure it looks like the following:

   ````
   {
       "image_dim_ordering": "tf",
       "epsilon": 1e-07,
       "floatx": "float32",
       "backend": "tensorflow"
   }
   ````

Then you can run the code via typing `jupyter notebook` into terminal

## Credits
The credits for this code go to [hnarayanan](https://github.com/hnarayanan/artistic-style-transfer). 




