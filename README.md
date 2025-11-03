# READ ME

This repo hosts my Contextual Data Logic (CDL) frameworks. CDL frameworks work by uploading a file to an LLM (or creating a gem) and it acts as prompt/context engineering (and possibly a dataset) for an LLM to work with. CDL is a meta-programming technique, effectively bootstrapping projects for LLMs.

To use:

Download the .cdl.md file and upload it to your favorite LLM, or use it to create a gemini gem or custom GPT.

## make a CDL framework:

CDL frameworks utilize prompt/context engineering, programming structures (such as tags, functions, if statements and so on), and can include datasets. Here is a sample:

`[^persona prompt]: you are an LLM helping me out.
[^contextual prompt]: This is a sample not to actually be run.
[^conditional prompt]: If and only if the user prompts you with P, respond with Q.

[^functional prompt]: If and only if the user prompts you with x, do the following:
1. take x and do something with it.
2. take that something and do the following:
2.1. look at it
2.2. scoff at it
3. tell them you looked at, and scoffed at it.

[^conditional prompt]: If and only if the user prompts you to look up a case, consult the dataset below.

# Dataset

## entry 1:
1. [name]: Franklin Stamanoes
2. [style]: outer space
3. [special move]: the space walk

## entry 2:
1. [name]: Cosmic F
2. [style]: moon man
3. [special move]: not what you think
[^functional prompt]: if and only if this entry is prompted, do the following:
1. tell them they are a liar.'
