# Guassian Naive Bayes

The repo contains materials for Flatiron School, London's Guassian Naive Bayes Clasifier lecture.
Materials for this lecture were originally developed by David John Baker.

## Materials

* [Slides](https://docs.google.com/presentation/d/16ybI_0nQ-f4pdVrfma5k3JOr5I7HFYoIYK3CiJdU5mA/edit?usp=sharing)
* [Exit Ticket]() 

## Learning Objectives 

By the end of the lesson, the student should be able to:

* [ ] Recognize situations where GNB can be applied 
* [ ] Explain what assumptions are needed for predictors and prediction classes in the model 
* [ ] Give an example of when GNB could be applied outside of examples used in the lecture
* [ ] Run the GNB algorithm with code from the lesson notebook
* [ ] Evaluate the output of a GNB classification algorithm 
* [ ] Pros and Cons of NBC 
* [ ] Explain what is "naive" about Naive Bayes Classifiers  

## Outline 

> Lesson Time: 90 Minutes
> 30 Minute Examples
> 10 Minute Break
> 30 Minute Hands On  

- Example
	- If I tell you XYZ 
	- What about second example
	- Again, situation here where formalise
	- 2 or more variables with normal distribution and 2 classes 
- Needed to Formalise 
	- Gaussian Distribution
	- Multivariate Guassian Distribution 
	- Classes 
	- Class Probabilites aka Prior 
	- Create Gausian for both varibles (mean and sd for both variables) 
	- Independence Assumption (multiply together to get MV gaussian) 
	- Draw Example 
	- End: How does this fit with Bayes from before?
	- Double Plot with seaborn 
- Running it in Python	
	- Variable I
	- Variable II
	- Classes (also SNS plot) 
	- New Point 
	- Look at point with Variable I
	- Look at point with Variable II 
	- Varible I distance on X axis 
	- Look at all 4 probability for EACH gaussian
	- Add in Latex Math 
	- First run model with Bayes formula as child
	- Then put in as adult 
	- Then use both of those probailities in computation
- Hands On 
- Exit Ticket 


## Further Resources 

* [Walk Through with Math](https://www.youtube.com/watch?v=r1in0YNetG8)  
* [Andrew Ng Walk Thru](https://www.youtube.com/watch?v=z5UQyCESW64)
* [More Andrew Ng](https://www.youtube.com/watch?v=NFd0ZQk5bR4)

## Notes

* What is naive 

* Generative Learning Example
	- Scales well 
	- Small datasets 
	- Great for not over designing 
	- Go to for classifier 
	- Don't look at both classes and separate
	- Start with one class, build model with what they look like
	- Start with other class, build model with what they look like 
	- Compare example to two models 
	- Learns p(x|y) 
	- What are features like conditioned on class 
	- relies on priors (no information whatsoever) 
	- Multiclass 

* Discriminative vs Generative 
	- Logistic Regression 
	- Estimate probability of y directly 
	- Learns p(y|x) "probability of y given x"



 
