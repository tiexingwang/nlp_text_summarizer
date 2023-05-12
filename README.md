# nlp_text_summarizer

Text Summarizer is a Python library that provides functionality to generate summaries of articles or texts. It uses a similarity-based approach to rank sentences and select the most important ones for summarization.

## Features

- Read and preprocess an article from a file
- Calculate sentence similarity based on word frequencies
- Build a similarity matrix representing pairwise similarity between sentences
- Rank sentences using the PageRank algorithm
- Select top-ranked sentences to generate the summary
- Plot the similarity matrix and PageRank scores for visualization
- 
## Usage

1. Create an instance of the `TextSummarizer` class:

```python
summarizer = TextSummarizer()
```

2. Generate a summary for an article:

```python
summary = summarizer.generate_summary('article.txt', top_n=3)
print(summary)
```

## Contributing

Contributions to Text Summarizer are welcome! If you find any issues or have suggestions for improvement, please create a GitHub issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.

## Acknowledgments

The Text Summarizer library was inspired by the concept of sentence similarity and the PageRank algorithm.

## References

- [Text Summarization using Sentence Similarity](https://www.analyticsvidhya.com/blog/2018/11/introduction-text-summarization-textrank-python/)
- [PageRank Algorithm](https://en.wikipedia.org/wiki/PageRank)
