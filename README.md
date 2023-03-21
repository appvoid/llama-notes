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
