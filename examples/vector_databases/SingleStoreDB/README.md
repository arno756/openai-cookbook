**[SingleStoreDB](https://singlestore.com)** has first-class support for vector search through our [Vector Functions](https://docs.singlestore.com/managed-service/en/reference/sql-reference/vector-functions.html). Our vector database subsystem, first made available in 2017 and subsequently enhanced, allows extremely fast nearest-neighbor search to find objects that are semantically similar, easily using SQL.

SingleStoreDB supports vectors and vector similarity search using dot_product (for cosine similarity) and euclidean_distance functions. These functions are used by our customers for applications including face recognition, visual product photo1 search and text-based semantic search [Aur23]. With the explosion of generative AI technology, these capabilities form a firm foundation for text-based AI chatbots.

## Examples

This folder contains examples of using SingleStoreDB and OpenAI together. We will keep adding more scenarios so stay tuned!

| Name | Description |
| --- | --- |
| [OpenAI wikipedia semantic search](./"OpenAI_wikipedia semantic_search".ipynb) | Improve GPT response accuracy by storing and running semantinc search over vectors from wikipedia pages |