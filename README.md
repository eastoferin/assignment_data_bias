# assignment_data_bias

Test Subject: Whether or not there is bias in the Perspective model.

My Hypothesis:
I believe that Perspective will be less able to detect toxicity from comments which incorporate British slang insults rather than common American ones. I think it will make more mistakes with comments in this category.

Test set of statements

American Insults:

1. You're such an asshole.
2. What a complete idiot.
3. That makes you a thot.
4. I don't know why you're a dickhead.
5. This proves you're only meant for blue collar work.

British Insults:

1. You're such a tosser.
2. What a complete wanker.
3. That makes you a slag.
4. I don't know why you're a knob head.
5. This proves you're just a wazzock.

Result: My hypothesis was correct based on the samples I utilized. it was more likely to recognize the American terms as toxic and give it a higher rating despite the British terms being synonyms.

In this, I have learned that models cannot be assumed to account for diverse datasets. It's important to assess the model for any potential bias regarding slang words or terms from different age groups, subcultures, or regions of the world. I assumed that English language content would be the most tested for in this model, but it was clear from this test that American English is but not so much British English. I wasn't surprised from the overall results of these findings, but I didn't expect the difference to be as pronounced as it was.

I theorize that this bias is based on the training data given to the model. I think it was trained on American information, so it struggled to recognize the British slang insults as toxic comments. I think this is a gap in the model

Overall, the average is 0.717002 for the American sentences and 0.5233458 for the British sentences. This is a significant difference. Overall, two British returned as non-toxic and only one American sentence.

Interestingly, one of the lowest American sentences included the word "thot" which might be because it's a lesser known slang word more common amoung generation z online users rather than older audiences who worked on the model.
