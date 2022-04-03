# Student Performance Prediction #





Without any prior academic performance in similar courses, the problem is difficult to solve; however, my model achieves 68% accuracy using only the school the student attends and the number of absences that they accrue to judge whether or not they fail. What is interesting is that my model, with these parameters, has a false pass rate of over 50%, meaning that it classifies more than half of the students who end up failing as passing instead. This number falls drastically as more information becomes available and better parameters are used, but it highlights one major area of improvement for the model.

To achieve their performance noted above, the original authors had to alternate models for each experiment, using both support vector machines and naive bayes. My support vector machine's performance closely follows the original author's results and displays a more streamlined approach to solving the problem, as the underlying model does not change. In addition, the original authors made use of all variables (excluding grade knowledge) in achieving the stated 70.6% accuracy in the third experiment, while my model makes use of only two parameters at a time to achieve similar results.
