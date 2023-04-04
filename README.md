# llama notes

### 15 Facts & Comments Collection
1. The hype on Twitter is surreal. llama models are not that powerful. At least not the smaller ones.
2. Benchmarks are little bit wrong. The more you use the model, the more you realize the subtle differences, weaknesess and strengths.
3. `llama-7b` is good, better than `gpt-j-6b` and `text-curie-001` but worse than `text-davinci-002`
4. `llama-13b` is as good as `text-davinci-002` when using a good prompt, in a multillingual setting though, is not that good.
5. I haven't tested `llama-30b` yet but given the observed tendency on performance, is presumably at the same level as `text-davinci-003`
6. The same goes for `llama-65b`, I assume it's just a little worse than `gpt-3.5-turbo`.
7. Notice that I'm talking about vanilla performance here, and that's why I understand the hype.
8. If a base model reaches similar performance to a fine-tuned one, that means that simply it's better.
9. All of this findings and thoughts should be taken with a grain of salt.
10. Assuming that `llama-alpaca-7b` is at the level of `text-davinci-002` and using the paper's benchmark as a reference, the following assumptions make sense:
- `llama-alpaca-7b` <= `text-davinci-002`
- `llama-alpaca-13b` <= `text-davinci-003`
- `llama-alpaca-30b` <= `gpt-3.5-turbo`
- `llama-alpaca-65b` <= `gpt-4`
11. A lot of people is simply loading those gigantic models not realizing that better use of gpu's vram is possible when using 4bit quantizing.
12. It's easy (and scary) to assume that right now, any smart-enough researcher with a relatively powerful gpu and training could (almost accidentally) oversee what none of us know and make an AGI sooner or later.
13. The statement above is even more scary when a lot of people dont't believe or even care that an AGI with this kind of technology is possible.
14. I bet llama models will surely reach gpt-4 level sooner or later.
15. Hopefully OpenAI or Google make an AGI before some random guy discovers how to overpower humanity itself, supposing that those companies don't do it first...

### 15 Facts & Comments Collection 1st Update: 4/4/2023
1. LLaMA models are actually pretty useless as factual agents yet a lot more powerful than expected when it comes to creative work generation.
2. llama.cpp got an update that let's you run 30b with just 6gb of ram.
3. Things are moving quickly. There are a lot of variations of the model but right now two of them worth mentioning which leads me to the next fact.
4. We now have GPT4ALL, a 7b model which is basically a fast, yet powerful version of ChatGPT. 
5. GPT4ALL is not as powerful as ChatGPT though. Its quality somewhat rivals `text-davinci-003` on some aspects, leaving aside multilingual tasks of course.
6. We also can use Vicuna, a 13b model which at the least on performance, is on par with powerful models like `bard` and `gpt-3.5-turbo`.
7. The fact that this level of quality was possible to achieve with maybe just one or two guys on a laptop it's amazing.
8. Also, terrifying since while a lot of ethical devs are asking for a license change for commercial purposes, there should already be a lot of companies using it specifically for profit. 
9. Also, if that's the case, given the high quality output of these models, no one would notice it. `bard` or `gpt-4` could be as well better fine-tuned llama models and no soul would notice it.
10. Seems like `vicuna-7b` is on the road. Hopefully it's better than `gpt4all`.
11. Fine-tuning llama models now seems to be possible even on a low-end 8gb vram card. That's crazy.
12. The fact that Microsoft claims that `gpt-4` has "sparks of AGI" is also something concerning. If it is true, there is nothing but OpenAI stopping people from fine-tunning `llama-65b` from `gpt-4` data. If we make a lot of "sparks" accesible, this could result into a fire, maybe literally.
13. As data continues to become accesible, people are less worried of not knowing something, this is a direct consequence of letting too much work to techonology, this fact also applies to models like `gpt-j`, `gpt-neo`, `cerebras-gpt` and `gpt-2`. LLaMA models are just making this automated case scenario easier.
14. I'm repeating myself, but for the sake of leaving it pretty clear: 
- If gpt-4 reaches AGI, llama could do it
- If llama can do it. We all can do it.
- If we all can do it, supposing that there is just one person that wants to watch the world burn, will try it.
15. As final fact, once we get LLaMA (or a better model) to be multimodal, I bet we will be entering, soon or later, to the age of highly optimized, safer robot assistants.
