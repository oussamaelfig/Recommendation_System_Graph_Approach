PageRank (PR) is an algorithm used by Google Search to rank websites in their search engine results. PageRank was named after Larry Page, one of the founders of Google. PageRank is a way of measuring the importance of website pages. According to Google:

PageRank works by counting the number and quality of links to a page to determine a rough estimate of how important the website is. The underlying assumption is that more important websites are likely to receive more links from other websites.

> It is not the only algorithm used by Google to order search engine results, but it is the first algorithm that was used by the company, and it is the best-known.

# Page Ranker’s Algorithm using python:-

![](https://miro.medium.com/v2/resize:fit:442/0*S8x3TYd5ApMb7CuO.jpg)

1.  Every webpage in google is stored as a node in a graph
2.  Every edge that is linked/directed to other node is the hyperlink in that webpage
3.  Based on this the graph looks like the above-illustrated Image
4.  As of now, the active website's count is nearly  **1,769,486,964.** So there will be billions of nodes connected with the graph. For Implementation purposes, I am using 25 nodes. There will be trillions of edges connected to the graph used by google.
