# Teachable-Machine-Lab-The-Desk-Object-Sorter-

A brief (1-2 sentence) description of your project. For example: "This project uses Google's Teachable Machine to classify common objects found on my desk."

## Classes Identified
List the objects your model was trained to identify:
* Class 1 (Scissors)
* Class 2 (Pen)
* Class 3 (Notebook)

## Discussion & Reflection

1.  **Model Performance & Iteration:**
    * How accurate was your first trained model? My first trained model had about 70-80% accuracy while indentifying the classes. 
    * What steps did you take to iterate and improve its performance? The steps I took to increase accuarcy where the same througout all 3 classes. I changed the background to get a more clear picutre. I elimanted glare. I rotated the object around more to create new angles and finally took more pictures(up to 50 with each)
    * How did these changes affect the model's accuracy and confidence scores? These changes boosted the modles accuracy and confidence score by giving it more than enough training to recognize the classes

2.  **Challenges & Observations:**
    * Which objects were the easiest for your model to learn and distinguish? Why do you think that was? The scissors were the easist for the model to recognize. I beleive that was the case because they have a distinct shape and pattern where the notebook and pen could be easily confused with other regular objects. The scissors were harder to mistake due to unique handles and shape blade coming out of them which is most likely why the model had no trouble with them.
    * Which objects were the most challenging? What made them difficult (e.g., similar shapes, variable appearances)? The pen was the most challenging for the model. What made it difficult was it's small size and common shape. The size of the pen was hard for the webcam to get a good angle on, and for the shape a ton of objects could look like that and with just a webcam it was tricky to get an angle/angles that helped solve the issue. 
    * What happened when you showed the model an object it wasn't trained on? How did the confidence scores behave, and why is this significant?
When I showed the model an untrained model it flucuated between 30% confidence between all three clasees. Showing the trained objects after helped increase the confidence scores in those objects
3.  **Bias in AI:**
    * If you only trained your "mug" class with images of *your specific mug* (and didn't vary color, shape, etc.), how well do you think it would recognize other students' significantly different mugs? How does this illustrate the concept of bias being introduced through training data?
    * Imagine all your training images were taken in very bright, direct lighting. What might happen if you tried to use the model in a dimly lit room or with strong shadows? How does this relate to the robustness and potential biases of AI models?
Both of those questions bring obvious problems into this training. It is most definatly bias to the exact objects I trained which tells me how important a wide variety and sample size of training is needed to create a solid model. The more training the better. 
4.  **Model Limitations & Usefulness:**
    * What are some key limitations of the model you created?
    * Why is it useful to be able to download your trained model files (like `model.json`, `weights.bin`) and share them (e.g., via GitHub)? What does this enable?
Key limitations of the model I created are not being able to recognize objects that weren't trained and trying to decide if any object is one of the 3 trained models. Downloading the trained model files enable the use of the training and futher usage, not just using it for a one time lab. 
5.  **Real-World Applications & Ethics:**
    * Brainstorm 2-3 real-world applications where a similar image classification model could be useful.
    * Briefly discuss one ethical consideration that developers should keep in mind when building and deploying image recognition AI in the real world (e.g., related to fairness, privacy, misuse).
The first real world example I can think of is a model that works in an airport that scans for potentially dangerous items with cameras. Another one is maybe and ID reader at the dmv.
An ethical problem I could see with AI image recognition in the real world is simply privacy. We were never meant to get to a point where walking down the street a camera could look at half of your face and then some system could pull up all the info there is on you. I understand security is important but privacy and rights are just as important. 
