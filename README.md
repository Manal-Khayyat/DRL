# Deep Reinforcement Learning For Arabic Image Retrieval

The image retrieval task requires a dynamic and interactive search system. Therefore, we formalize the image retrieval problem as a sequential decision-making problem, where the agent is considered the search engine. The environment sends an image by image to the agent for retrieving the most similar images to each query image. To solve the retrieval problem, the Deep Reinforcement Q-learning Network (DRQN) is used. It involves an end-to-end ordered interactions between the environment and the agent.

The code utilizes the fused visual and textual features extracted from the images to retrieve them more accurately.
It is enhanced using the hashing technique to reduce the dimensionality existed among the features and make the environment more stable by removing the randomness in the search process.
