A recent opensource software library called LangChain, started providing solutions for the steps of developing a custom AI app utilizing LLMs and gained much attention from the AI community.

The most important key building block of LangChain is the chain. The chain usually combines an LLM together with a prompt, and with this building block, you can also put a bunch of these building blocks together to carry out a sequence of operations on your text or on your other data. A simple chain takes one input prompt and produces an output. Multiple chains can be run one after another, where the output of the first chain becomes the input of the next chain.

A memory component is needed that can store the previous conversations and pass them to the LLM with the next prompt.

One of the most common and complex applications that are being built using an LLM is a system that can answer questions on top of or about a document



langchain can be used to interact with open sourc llm's, 
and with the help of tools like streamlit you can easily get an app up and running within minutes
.
requirements:
open-ai api key(optional)

we set up a prompt_template
set up the input parameters, 
and call invoke the template

things to refer:
chain in
sequential lang chain
using multiple llms
maintaining chat history
embeddings
vector stores


