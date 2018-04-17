# image
<h1>Making an apple recognizer using relu and other activations</h1>
Data is collected from <a>https://github.com/Horea94/Fruit-Images-Dataset</a>
Our training data looks like
<p align="center">
  <img src="https://github.com/aviralgoyal1997/image/blob/master/Screenshot%20from%202018-04-18%2002-19-23.png" width="500"/>
  <img src="https://github.com/aviralgoyal1997/image/blob/master/Screenshot%20from%202018-04-18%2002-27-26.png" width="500"/>
</p>
Similarly like training folder we have validation folder having 100 images of each category.
now as said in project I first applied cnn model with relu activation and got a nice accuracy and then in other files I did same with smooth relu and relu +cos activation function and got best accuracy with relu +cos.
After applying relu improving that accuracy more is kinda not possible but while taking new activation functions I took care that they are continuous and won't cause vanishing gradient problem.One problem with relu is that it breaks at 0 while smooth relu will not break at any point and relu+cosdivided data in better way than normal relu.
<p align="center">
  <h2>Relu+Cos</h2><img src="https://i.stack.imgur.com/18Fk9.png" width="500"/>
  <h2>Smooth Relu</h2><img src="https://i.stack.imgur.com/7Etfy.png" width="500"/>
</p>

