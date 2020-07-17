# Car-Price-Prediction
Predicting Reselling Price

This is a machine learning project that can be used to predict the reselling price of the cars with the help of the details of the car. This is an end to end project in python and written with the help of Flask and deployed using Heroku.

> ## Requirements:
> For Required package/module installation, open the terminal and copy paste below command:
> - pip install requirements.txt

> ## To Execute the code:
> Run the command in your terminal or command prompt.
> - python app.py \
> After running the the same, you will get your local host address, something like as shown below.
> ![image](https://user-images.githubusercontent.com/48138906/87266873-dea1fe00-c4e3-11ea-8a4a-f89f2cda54a2.png) \
> Open the same in your browser, the setup is now complete.

> The broswer opens to this.
> ![Screenshot from 2020-07-17 10-19-25](https://user-images.githubusercontent.com/48138906/87749736-217f1100-c817-11ea-9e0b-d371e74a5bcf.png)


> You can now predict the price of your car before reselling it.

> ## Notebook.ipynb
> This python notebook has the code for the machine learning model which is trained using the data provided in "data.csv", the model is then dumped using pickle and further used to predict values using Flask.
> The accuracy of the model is 87% which can be increased with hyper parameter optimization or with the help of more data.
> I have used pickle to dump the model to further use it for deployment.
> ## Heroku
> I have used Heroku cloud services to deploy the same and the link for the same can be found here:
> https://predictingcarprice.herokuapp.com/

> Do star the repository, also suggestions and changes are most welcome.

# Note:
 > Having a seperate environment setup is always expected to follow.

