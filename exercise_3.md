# Exercise 3: Using Delimiters to Define Context

**Objective:** Restrict responses to a specific block of text.

Place a passage inside delimiters (### or triple backticks).

Add instructions: “Answer using only the text inside the delimiters.”

Compare the output with and without delimiters to see the effect.

-----

**Passage**
```
I get asked this question a lot: what's your favourite episode of The Diary Of A CEO ever?

The answer is fairly easy.. episode 101 with Mo Gawdat. It was our most shared episode ever, not because of fame or celebrity, but because what he said was so profound it changed the way I think about life..

Mo was the Chief Business Officer at Google X, the "moonshot factory" behind self-driving cars and some of the most futuristic technology on the planet. He co-founded over 20 businesses. By any external measure, he had achieved everything. But he was desperately unhappy...
```

**The prompt I gave to the model:**
- What was Mo Gawdat former position at Google?
- Answer using only the text inside the delimiters (back tick)


---
**The output without the prompt instruction**
Mo Gawdat’s former position at Google X was Chief Business Officer (CBO)

**The output with the prompt instruction**
Chief Business Officer at Google X

## My Observation
**The first sentence without the instruction:**
- uses outside knowledge context (treats it as a real-world factual question).
- Slightly reformats the answer
- Not strictly constrained to the exact wording from the passage

**The second output with the instruction:**
- Uses the only the text inside the backticks
- Does not add interpretation
- Does not rephrase
- Simply extracts the word from the provided passage
