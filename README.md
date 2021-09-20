# BechdelTest 
Automating the Bechdel Test by analyzing the movie script
- the AI portion of Spotlight

### Created for Spotlight
[Head over to our project on Devpost](https://devpost.com/software/spotlight-7yur8f)


<h2>Inspiration</h2>

<p>Media is the most powerful influencer of how we view genders. With media being everywhere it’s bound to shape the way we view the two genders from a young age. Young girls grow up with an incorrect assumption of how they should behave and their role within society </p>

<blockquote>
<p>Women have a right to be equally represented on film
Instead we commonly see that women are underrepresented in media. This results in an unconscious bias that women are unimportant and hidden. 
Men and women are stereo-typically represented
Men and women are also represented in ways that are stereotypical and reflect traditionally endorsed views of gender. Men are commonly portrayed to have more power, wealth, and authority while women are seen as passive, relationship-driven, and meek. This distorted version of gender being identity affects the actual culture in our countries through their pervasive messages woven throughout our lives.</p>
</blockquote>

<p>Which is why we choose to automate the Bechdel Test with AI. The Bechdel test is a litmus test to evaluate the presence of women in media. Films have three requirements to pass:</p>

<ol>
<li>It must have two women</li>
<li>Who have one conversation</li>
<li>About something that is not a man/men
It may seem really simple and easy to meet, yet it is proven that only around half of the movies pass this test. Much of the mainstream media doesn’t pass this simple test. You should also try it the next time you watch a movie.</li>
</ol>

<p>The Bechdel test isn’t designed as a moral judgement of “your movie is horrible” it’s like a quick check or reminder that there might be a lack of representation in your film.</p>

<h2>What it does</h2>

<p>We built an automated version of the Bechdel test. By using AI we can predict which genders are talking at which time. Our website would return a score of:</p>

<ol>
<li> If the script has two women.</li>
<li>If they talk to each other (two women dialogue tags in succession)</li>
<li>About something other than men (check if they mention men in their conversation)</li>
</ol>

<h2>How we built it</h2>

<p>We used jupyter notebook to create the model of the Bechdel test, then we hosted API and created the front end design of our web application. This project uses Python for the Bechdel test model, HTML &amp; CSS for the front end, and React for the back end.</p>

<h2>Challenges we ran into</h2>

<p>We had a lot of difficulty with sending and receiving requests. Since neither of us are that familiar with React, we were conducting a lot of testing on Postman to try to debug the problem. We soon realized that it was an issue with the form tag in HTML and got the project up and running.</p>

<h2>Accomplishments that we're proud of</h2>

<p>Overall, we're quite proud of all that we've learnt and accomplished on such a short time frame. Seeing this project come to life from the ground up was a very novel experience.</p>

<h2>What we learned</h2>

<p>When we were just starting out with the project we were shocked by the amount of movies that didn't pass the Bechdel test. This definitely provided us with a deeper understanding of gender in the media.</p>

<h2>What's next for Spotlight</h2>

<p>There are a few things we would like to expand and iterate on if we had more time.
Certain aspects of the design and structure of the application can be improved and making sure the entire user experience is simple and clean. 
We could also shift and do another evaluation of bias aside from the Bechdel test. For example analyzing the script to predict the amount of gender bias (apart from the 3 score format of the Bechdel test), or using computer vision to analyze the shots of the movie directly (although this would be much harder for a director to change, compared to a script).</p>
