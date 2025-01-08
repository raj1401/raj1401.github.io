# Machine Learning Engineer

#### Technical Skills: Python, C++, CUDA C++, Azure, AWS, Docker, PyTorch

## Education
- M.S., Computer Science	 |         The University of Illinois at Chicago (_May 2025_)
- B.S., Physics (Research) | Indian Institute of Science (IISc), Bangalore (_May 2023_)

## Work Experience
**Graduate Research Assistant @ Discovery Partners Institute (_October 2023 - Present_)**
- Spearheaded the design and development of *Bluegill*, an autonomic AI platform enabling secure, distributed training of explainable AI models.
- Led a multidisciplinary team, managing two week sprints, conducting code reviews, and collaborating with over 10 research teams, boosting research efficiency by 50%.
- Implemented robust CI/CD pipelines using GitHub Actions and used Agile practices to streamline development, automate testing, and ensure seamless deployment.
- Improved user satisfaction by 30% and improved user experience by providing a privacy-focused LLM-based chatbot integrated into the platform.
- **Tech Stack**: PostgreSQL, Angular, Python, Microsoft Azure

**Undergraduate Research Engineer @ Cancer Systems Lab, IISc (_May 2022 - July 2023_)**
- Directed the development of a high-performance genomic data storage and retrieval system and utilized deep learning to achieve 98% accuracy on Gene Regulatory Networks (GRNs) prediction.
- Engineered a parallelized framework optimized for high-performance computing systems to train deep learning models on time-series gene interaction data and accurately predict GRNs, significantly enhancing data processing efficiency and scalability.

## Projects & Research
### MS Thesis - Diffusion Models for 3D Reconstruction
Designed and implemented a deep learning framework that utilizes Denoising Diffusion Probabilistic Model (DDPM) architecture to learn Gaussian ellipsoid representation of 3D scenes. The trained model can be used to generate novel 3D scenes. Devised a multi-view guided sampling strategy to guide sampling from the trained DDPM in order to achieve desirable 3D scenes.

[Link to Repository](https://github.com/raj1401/Diffusion-Gaussian-Splatting)

### Retrieval Augmented Generation (RAG) Chatbot
Designed an RAG chatbot that runs your LLM of choice locally using Llama-cpp, refines the context by extracting relevant embeddings of documents from a vector database, and responds to user queries accordingly. The embeddings of the documents provided by the user are created using the all-MiniLM-L6-v2 sentence-transformer, which are then stored in a Chroma vector database. Based on the user query and chat history, the current context is sequentially refined using relevant document chunks fetched from the database, before using a local LLM, such as Llama-3.1-8B, to generate the answer.

![RAG Chatbot Implementation](assets/img/RAG_Chatbot_Diagram.jpg)

[Link to Repository](https://github.com/raj1401/RAG-Chatbot)

### Video Frame Interpolation - IFRNet Optimization
Overhauled the Intermediate Feature Refine Network (IFRNet) architecture, enabling real-time video frame interpolation while maintaining high performance and visual stability. The first strategy was to reduce the depth of the model, achieving 21% reduction in model size and only 0.36% reduction in PSNR. The second strategy was to reduce the number of channels in the model, with which a 55% reduction in model size was achieved with only 2.28% degradation in PSNR. These lighter models can enable use of IFRNet on edge devices for real-time video frame interpolation, boosting the smoothness of videos stored locally and streamed from the internet.

![IFRNet Architecture](assets/img/IFRNet_Diagram.jpg)

[Link to Repository](https://github.com/raj1401/Video-Frame-Interpolation-IFRNet)

### Uncensoring Large Language Models using Abliteration
Implemented weight orthogonalization techniques on the Meta Llama-3.1-8B model, enabling responses to restricted prompts with only a 1% performance reduction on MMLU and TruthfulQA benchmarks.

[Link to Repository](https://github.com/raj1401/Uncensoring-LLMs-with-Abliteration)

### Automatic Music Generation using VAEs
Trained a Variational AutoEncoder on MIDI files of classical music by artists such as Beethoven to learn the latent representation of it, and generate new music as a directed random walk in the latent space.

[Link to Repository](https://github.com/raj1401/Automatic-Music-Generation-VAE)

### BS Thesis - Deducing Gene Regulatory Networks using Machine Learning
Developed a deep learning framework that solves the inverse problem of constructing Gene Regulatory Networks (GRNs) from gene expression time-series data. The framework was developed so that it easily scales training over various nodes of a HPC cluster. It was validated over the toggle switch and toggle triad networks, which are considered to be fundamental network motifs. Further showed how such a framework can be used to refine results further using edge-deletion and retraining techniques.

[Link to Repository](https://github.com/raj1401/Deducing-GRNs-Using-ML)

#### View all projects on [GitHub](https://github.com/raj1401?tab=repositories)

## Awards and Achievements
- **IBM Quantum** (_2021_): Ranked top 5 in IBM's 2021 Global cohort in Quantum Machine Learning and received the [Certificate of Quantum Excellence](https://drive.google.com/file/d/1tvF_El8Z8HbEZylX7orT2sRt7g1OB9EP/view?usp=sharing).
- **KVPY** (_2019_): Ranked 227 nationally (top 0.01%) in the Kishore Vaigyanik Protsahana Yojana (KVPY) exam conducted by the Department of Science and Technology, India. Received fully-funded scholarship for four years to pursue my Bachelor's degree at the Indian Institute of Science (IISc), Bangalore, India's premier institute for research education.
- **PRL** (_2017_): Achieved a top 5 rank in a state-wide competition organized by the Physical Research Laboratory-ISRO and was awarded a two year scholarship to pursue higher secondary education.
