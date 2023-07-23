# SemEval2024 Task 8

Large language models (LLMs) are becoming mainstream and easily accessible, ushering in an explosion of machine-generated content over various channels, such as news, social media, question-answering forums, educational, and even academic contexts. Recent LLMs, such as ChatGPT and GPT4, generate remarkably fluent responses to a wide variety of user queries. The articulate nature of such generated text makes LLMs attractive for replacing human labor in many scenarios. 
However, this has also resulted in concerns regarding their potential misuse, such as spreading misinformation and causing disruptions in the education system.

Since humans perform only slightly better than chance when classifying machine-generated vs. human-written text, there is a need to develop automatic systems to identify machine-generated text with the goal of mitigating its potential misuse. With this in mind, we offer three subtasks over two paradigms of text generation: (1) **full text** completely written by humans or generated by a machine; and (2) **mixed text** (machine-generated text refined by human or human-written text paraphrased by a machine).

**Subtask A. Binary Human-Written vs. Machine-Generated Text Classification:** Given a full text, determine whether it is human-written or machine-generated.

**Subtask B. Multi-Way Machine-Generated Text Classification:** Given a full text, determine who generated it. It can be human-written or generated by a specific language model.

**Subtask C. Human-Machine Mixed Text Detection:** Given a mixed text, where the first part is human-written and the second part is machine-generated, determine the boundary, where the change occurs.

Sample data for subtasks A and B can be found here:
https://drive.google.com/file/d/17XCvku88CjJJ5LdlUAcMGGwP1Jt6nudQ/view?usp=sharing

Sample data for subtask C is in the repository

See also some preliminary experiments with the data in this [document](https://arxiv.org/abs/2305.14902):

@misc{wang2023m4,
      title={M4: Multi-generator, Multi-domain, and Multi-lingual Black-Box Machine-Generated Text Detection}, 
      author={Yuxia Wang and Jonibek Mansurov and Petar Ivanov and Jinyan Su and Artem Shelmanov and Akim Tsvigun and Chenxi Whitehouse and Osama Mohammed Afzal and Tarek Mahmoud and Alham Fikri Aji and Preslav Nakov},
      year={2023},
      eprint={2305.14902},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
