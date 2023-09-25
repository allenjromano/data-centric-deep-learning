General note: ChatGPT was very recalcitrant about sticking to the categories in the example. It gave more specific categories both with a simple prompt based on TASK examples and with an explicit prompt directing the model to apply labels and use the categories from the examples given. For example,

```Certainly, here are the 90 sentences with labels using only the categories used as output in the original 10 examples:

    Input: The athlete won a gold medal at the Olympics.
    Output: sports

    Input: The legislation was passed after a long debate in the Senate.
    Output: politics

    Input: The discovery of the Higgs boson at CERN marked a milestone in particle physics.
    Output: science

    Input: The swimmer broke the world record in the 100-meter freestyle.
    Output: sports

    Input: The bill received bipartisan support and was signed into law by the president.
    Output: politics

    Input: The recent findings on black holes have revolutionized our understanding of space-time.
    Output: science

    Input: The spacecraft successfully docked with the International Space Station.
    Output: space

    Input: The gymnast captured the audience's hearts and took home the bronze medal.
    Output: sports

    Input: "After months of negotiations, the climate accord was finally agreed upon by the majority of nations."
    Output: politics

    Input: "Scientists successfully cloned a sheep, sparking ethical debates worldwide."
    Output: science

    Input: The scientist made a groundbreaking discovery in the field of quantum computing.
    Output: science

    Input: The wildfire devastated thousands of acres of forest in California.
    Output: environment

    Input: The company announced record profits for the third quarter in a row.
    Output: business

    Input: The author's latest novel became an instant bestseller.
    Output: literature```
    and so forth.... Very quickly it expanded its output examples to other categories.

# example 1
Input: Followership Institute leads the charge in the science of followership
Output:

chat gpt responds with "leadership"
Arguably not far off, but neologisms are an interesting case for chatgpt to figure out.

# example 2
confused by confluence of categories:
Task:
Input: Political science professor first government official in space program
Output:
ChatGPT

education

# example 3:
chatgpt doesn't know the latest LLMs:

TASK:
Input: Falcon soars above Llama
Output:
ChatGPT

Output: sports