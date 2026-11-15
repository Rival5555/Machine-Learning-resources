# Machine Learning Resources

> A curated, file-based library for studying machine learning, data science, mathematics, engineering practices, research, and related subjects.

## Table of Contents

- [Introduction](#introduction)
- [Repository Highlights](#repository-highlights)
- [Learning Categories](#learning-categories)
- [Repository Structure](#repository-structure)
- [Learning Resources](#learning-resources)
- [Recommended Learning Approach](#recommended-learning-approach)
- [How to Use This Repository](#how-to-use-this-repository)
- [Contribution Guidelines](#contribution-guidelines)
- [Repository Goals](#repository-goals)
- [License and Attribution](#license-and-attribution)
- [Author / Maintainer](#author--maintainer)

## Introduction

Machine Learning Resources is a personal collection of study materials gathered for self-directed learning and knowledge sharing. It is not a software application or a single course: it is an organized archive of PDFs, research papers, reference books, roadmaps, course material, and practical Jupyter notebooks.

The collection is useful for beginners building foundations, practitioners revising specific topics, and readers looking for references across the machine-learning lifecycle. Materials cover theory, mathematics, implementation-oriented subjects, research, delivery practices, and complementary professional skills.

## Repository Highlights

- **224 PDFs** covering technical notes, books, course material, papers, checklists, and reference guides.
- **6 Jupyter notebooks** with exercises and assignments for model evaluation, anomaly detection, clustering, and recommender systems.
- Dedicated material for **machine learning, deep learning, data science, mathematics, NLP, LLMs, computer vision, and MLOps**.
- Supporting resources for **Docker, cybersecurity, software product management, linear algebra, and broader political and social reading**.
- A focused **data science roadmap** with resume and LinkedIn checklists.
- A research collection covering **deepfakes, face swapping, crowd counting, age and gender classification, and transformers**.

## Learning Categories

| Category | What you can study | Location |
| --- | --- | --- |
| Machine learning and deep learning | Regression, classification, SVMs, tree-based methods, neural networks, CNNs, TensorFlow, PyTorch, NLP, transformers, LLMs, and computer vision | [`ML & DL/`](./ML%20%26%20DL/) |
| Data science and statistics | Data-science foundations, SQL, probability, statistics, analytics, and a 2024 roadmap | [`Data Science notes/`](./Data%20Science%20notes/) |
| Mathematics for ML | Linear algebra, calculus, vector calculus, and mathematical foundations | [`LA for ML/`](./LA%20for%20%20ML/) and [`ML & DL/`](./ML%20%26%20DL/) |
| Practical ML labs | Model evaluation, anomaly detection, K-means, and collaborative-filtering assignments | [`ML & DL/labs/`](./ML%20%26%20DL/labs/) |
| Research papers | Deep learning, deepfakes, face swapping, crowd counting, age and gender prediction, and attention-based models | [`Research papers/`](./Research%20papers/) |
| MLOps and delivery | MLOps concepts, model training, CI/CD for ML, Git, GitHub, and Docker | [`mlops/`](./mlops/) and [`Docker resources/`](./Docker%20resources/) |
| Cybersecurity and Linux | Ethical hacking, information security, Tor, Kali Linux, Linux programming, and Arch Linux setup | [`Cybersecurity/`](./Cybersecurity/) |
| Software product management | Software processes, Agile practices, client needs, software requirements, glossaries, and course maps | [`software product management/`](./software%20product%20management/) |
| Books and wider reading | Politics, history, economics, philosophy, religion, psychology, leadership, productivity, and society | [`Political Books/`](./Political%20Books/) |

## Repository Structure

```text
.
├── Cybersecurity/                 # 6 PDFs; one temporary artifact
├── Data Science notes/            # 12 PDFs
│   └── data-science-roadmap-2024/ # Roadmap, LinkedIn, and resume checklists
├── DataScience/                   # One temporary artifact
├── Docker resources/              # 4 Docker chapter PDFs
├── LA for  ML/                    # 5 linear-algebra resources
├── ML & DL/                       # 71 PDFs on ML, DL, NLP, LLMs, and related topics
│   └── labs/                      # 6 Jupyter notebooks and assignments
├── Political Books/               # 92 PDFs and one image
├── Research papers/               # 15 research papers
├── mlops/                         # 9 MLOps and Git/GitHub PDFs
├── software product management/   # 10 course and glossary PDFs
├── .gitignore
└── README.md
```

The `.temp` files in `Cybersecurity/` and `DataScience/` are retained repository artifacts, not documented learning resources. The image in `Political Books/` is also not presented as a study item.

## Learning Resources

### Foundations and study planning

| Resource | Type | Link |
| --- | --- | --- |
| Data Science Roadmap 2024 | Roadmap PDF | [`DS_2024_Roadmap.pdf`](./Data%20Science%20notes/data-science-roadmap-2024/DS_2024_Roadmap.pdf) |
| LinkedIn Checklist | Career checklist PDF | [`LinkedIn Checklist.pdf`](./Data%20Science%20notes/data-science-roadmap-2024/LinkedIn%20Checklist.pdf) |
| Resume Checklist | Career checklist PDF | [`Resume Checklist.pdf`](./Data%20Science%20notes/data-science-roadmap-2024/Resume%20Checklist.pdf) |
| Foundations of Data Science | Notes / reference PDF | [`Foundations_of_Data_Science.pdf`](./Data%20Science%20notes/Foundations_of_Data_Science.pdf) |
| Statistics & Probability for Data Analytics | Statistics reference PDF | [`Statistics & Probability For Data Analytics.pdf`](./Data%20Science%20notes/Statistics%20%26%20Probability%20For%20Data%20Analytics.pdf) |

### Machine learning, deep learning, and tools

| Resource | Type | Link |
| --- | --- | --- |
| Python for ML | Python / ML notes PDF | [`Python For ML.pdf`](./ML%20%26%20DL/Python%20For%20ML.pdf) |
| Mathematics of Machine Learning | Mathematics reference PDF | [`Mathematics of Machine Learning.pdf`](./ML%20%26%20DL/Mathematics%20of%20Machine%20Learning.pdf) |
| Supervised and Unsupervised Learning | ML concepts PDF | [`Supervised and Unsupervised Learning.pdf`](./ML%20%26%20DL/Supervised%20and%20Unsupervised%20Learning.pdf) |
| Neural Network Classification with TensorFlow | Framework tutorial PDF | [`Neural Network Classification with TensorFlow.pdf`](./ML%20%26%20DL/Neural%20Network%20Classification%20with%20TensorFlow.pdf) |
| PyTorch neural network classification | Framework tutorial PDF | [`Pytorch neural network classification .pdf`](./ML%20%26%20DL/Pytorch%20neural%20network%20classification%20.pdf) |
| Natural Language Processing | NLP reference PDF | [`Natural Language Processing.pdf`](./ML%20%26%20DL/Natural%20Language%20Processing.pdf) |
| A Beginner's Guide to Fine-Tuning LLMs | LLM guide PDF | [`A Beginner's Guide to Fine Tuning LLMs.pdf`](./ML%20%26%20DL/A%20Beginner%27s%20Guide%20to%20Fine%20Tuning%20LLMs.pdf) |
| Scikit-learn Notes | Library notes PDF | [`Scikit learn Notes.pdf`](./ML%20%26%20DL/Scikit%20learn%20Notes.pdf) |

### Practical notebooks

| Notebook | Focus | Link |
| --- | --- | --- |
| Model Evaluation and Selection | Evaluation and model selection | [`C2W3_Lab_01_Model_Evaluation_and_Selection.ipynb`](./ML%20%26%20DL/labs/C2W3_Lab_01_Model_Evaluation_and_Selection.ipynb) |
| Anomaly Detection | Anomaly detection | [`C3_W1_Anomaly_Detection.ipynb`](./ML%20%26%20DL/labs/C3_W1_Anomaly_Detection.ipynb) |
| K-Means Assignment | Clustering | [`C3_W1_KMeans_Assignment.ipynb`](./ML%20%26%20DL/labs/C3_W1_KMeans_Assignment.ipynb) |
| Collaborative Filtering Assignment | Recommender systems | [`C3_W2_Collaborative_RecSys_Assignment.ipynb`](./ML%20%26%20DL/labs/C3_W2_Collaborative_RecSys_Assignment.ipynb) |
| Recommender Systems Neural Network Assignment | Recommender systems | [`C3_W2_RecSysNN_Assignment.ipynb`](./ML%20%26%20DL/labs/C3_W2_RecSysNN_Assignment.ipynb) |
| Course assignment | ML assignment material | [`C3_W3_A1_Assignment.ipynb`](./ML%20%26%20DL/labs/C3_W3_A1_Assignment.ipynb) |

### Research and engineering practice

| Area | Examples | Link |
| --- | --- | --- |
| Research papers | Attention, DeepSeek-R1, deepfakes, face swapping, crowd counting, and age/gender prediction | [`Research papers/`](./Research%20papers/) |
| MLOps | MLOps concepts, model training, CI/CD, and Git/GitHub | [`mlops/`](./mlops/) |
| Docker | Four chapter resources | [`Docker resources/`](./Docker%20resources/) |
| Cybersecurity | Security, Linux, Tor, Kali Linux, and ethical hacking | [`Cybersecurity/`](./Cybersecurity/) |
| Software product management | Three course areas with course maps and glossaries | [`software product management/`](./software%20product%20management/) |

<details>
<summary>Browse the complete collection by directory</summary>

The complete archive is intentionally kept in its subject directories. Open a directory below to browse every verified file it contains:

- [`Data Science notes/`](./Data%20Science%20notes/)
- [`ML & DL/`](./ML%20%26%20DL/)
- [`ML & DL/labs/`](./ML%20%26%20DL/labs/)
- [`Political Books/`](./Political%20Books/)
- [`Research papers/`](./Research%20papers/)
- [`mlops/`](./mlops/)
- [`Docker resources/`](./Docker%20resources/)
- [`LA for ML/`](./LA%20for%20%20ML/)
- [`Cybersecurity/`](./Cybersecurity/)
- [`software product management/`](./software%20product%20management/)

</details>

## Recommended Learning Approach

The repository does not prescribe a single course sequence, but its contents support this flexible workflow:

1. Use the [data science roadmap](./Data%20Science%20notes/data-science-roadmap-2024/DS_2024_Roadmap.pdf) to orient your study and identify foundational gaps.
2. Review mathematics and statistics in [`LA for ML/`](./LA%20for%20%20ML/) and [`Data Science notes/`](./Data%20Science%20notes/).
3. Study core ML concepts and then move into deep learning, NLP, LLM, or computer-vision topics in [`ML & DL/`](./ML%20%26%20DL/).
4. Reinforce concepts with the notebooks in [`ML & DL/labs/`](./ML%20%26%20DL/labs/).
5. Read related papers in [`Research papers/`](./Research%20papers/) when you want to connect concepts with current research themes.
6. Explore [`mlops/`](./mlops/) and [`Docker resources/`](./Docker%20resources/) for packaging, delivery, and operational practices.

Use the books, cybersecurity materials, and software product-management courses as complementary reading rather than as prerequisites for the ML material.

## How to Use This Repository

### Browse online

Open a subject directory above, then select a PDF or notebook. GitHub can preview many PDFs and notebooks directly; large files may be easier to download locally.

### Clone locally

```bash
git clone https://github.com/Rival5555/Machine-Learning-resources.git
cd Machine-Learning-resources
```

### Keep a local copy updated

```bash
git pull --ff-only origin main
```

You can open PDFs with your preferred PDF reader and launch notebooks with Jupyter or another compatible notebook environment:

```bash
jupyter notebook
```

No dependency manifest or executable application is included, so the exact environment required for a particular notebook should be checked inside that notebook before running it.

## Contribution Guidelines

Contributions should improve the collection's usefulness and organization:

1. Add educational material that fits an existing subject area.
2. Place new files in the most specific appropriate directory.
3. Use descriptive filenames and preserve the existing naming style where possible.
4. Fix broken paths or improve this README when the repository changes.
5. Add notebooks or notes with enough context for another learner to understand their purpose.
6. Avoid committing secrets, unrelated personal files, or duplicate resources.
7. Respect copyright, licenses, and the redistribution terms of every resource.

For substantial additions, describe the subject, source, and intended audience in the pull request or commit message.

## Repository Goals

This repository aims to make useful learning material easier to discover, revisit, and share. Its value comes from clear organization and responsible maintenance: learners should be able to find foundational references, practical exercises, research material, and complementary professional topics without searching through an unstructured archive.

## License and Attribution

No repository license file was found. Therefore, the repository should not be assumed to grant permission to redistribute, modify, or commercially use the included materials.

Many files appear to be books, papers, course documents, or other externally authored works. Please verify the original copyright, license, and distribution terms before downloading, redistributing, or contributing any material. When adding a resource, preserve its author and source information where available.

## Author / Maintainer

The repository is maintained by [Rival5555](https://github.com/Rival5555). The Git history identifies the maintainer as Rival5555; contributions and corrections are welcome through normal GitHub collaboration workflows.
