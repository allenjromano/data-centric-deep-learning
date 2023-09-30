Original prompt for generating sentences and labels: (note: modified to generate and label in a single pass)
```
Make 90 examples of Input sentences similar in form to those in the following list of examples. Print with the same format of "Input:" followed by the new sentence and then "Output:" followed by a keyword describing the category. The Output category keyword must be one of the words in the following list: sports, politics, science. List the single category that comes closest to matching the sentence Input.

Examples:

Input: The athlete won a gold medal at the Olympics. Output: sports

Input: The legislation was passed after a long debate in the Senate. Output: politics

Input: The discovery of the Higgs boson at CERN marked a milestone in particle physics. Output: science

Input: The swimmer broke the world record in the 100-meter freestyle. Output: sports

Input: The bill received bipartisan support and was signed into law by the president. Output: politics

Input: The recent findings on black holes have revolutionized our understanding of space-time. Output: science

Input: The spacecraft successfully docked with the International Space Station. Output: science

Input: The gymnast captured the audience's hearts and took home the bronze medal. Output: sports

Input: "After months of negotiations, the climate accord was finally agreed upon by the majority of nations." Output: politics

Input: "Scientists successfully cloned a sheep, sparking ethical debates worldwide." Output: science
```

Given those constraints, chatgpt sticks to its categories. However, with a different prompt (closer to the one given in the instructions) which does not specify labeling so strictly and relies instead on few shot learning, it is possible to trick chatgpt into giving more specific and misleading categories

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
chatgpt doesn't know the latest LLMs and connects Falcon with, most likely, the Atlanta Falcons:

TASK:
Input: Falcon soars above Llama
Output:
ChatGPT

Output: sports