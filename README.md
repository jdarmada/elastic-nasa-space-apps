# elastic-nasa-space-apps


### Getting Started with Elastic
- [Elastic Fundamentals & Docs Hub](https://www.elastic.co/docs/get-started/)
- [ESQL reference](https://www.elastic.co/docs/reference/query-languages/esql)

---

### Agent Builder
- [Agent Builder Intro Tutorial (YouTube)](https://www.youtube.com/watch?v=VfEksBT0JBw&t=968s)
- [Agent Builder Overview Article](https://www.elastic.co/search-labs/blog/ai-agentic-workflows-elastic-ai-agent-builder)
- [Agent Builder Example (Deep Dive)](https://www.elastic.co/search-labs/blog/ai-agent-builder-elasticsearch)

---

### Search & Analytics
- [Geo Queries](https://www.elastic.co/docs/reference/query-languages/query-dsl/geo-queries)
- [Geospatial Analysis](https://www.elastic.co/docs/explore-analyze/geospatial-analysis)
- [Vector Search](https://www.elastic.co/docs/solutions/search/vector)
- [Hybrid Search (Combining Vector + Keyword)](https://www.elastic.co/docs/solutions/search/hybrid-search)

---

### Language Clients
Use any major programming language to interact with Elasticsearch:

- [Python Client](https://www.elastic.co/docs/reference/elasticsearch/clients/python)
- [JavaScript Client](https://www.elastic.co/docs/reference/elasticsearch/clients/javascript)
- [Java Client](https://www.elastic.co/docs/reference/elasticsearch/clients/java)
- [Go Client](https://www.elastic.co/docs/reference/elasticsearch/clients/go)
- [Rust Client](https://www.elastic.co/docs/reference/elasticsearch/clients/rust)

---




## How to enable Agent Builder

1. Go to [https://cloud.elastic.co/registration](https://cloud.elastic.co/registration) and sign up for a free trial.
2. Click on the **serverless** deployment type and Elasticsearch focus.
3. Once your serverless deployment is up and running, click on the **Developer Tools** on the bottom left.
   
 <img width="248" height="57" alt="Screenshot 2025-10-04 at 2 59 30 PM" src="https://github.com/user-attachments/assets/4062b4dc-c26b-43b3-a992-93b1864c836b" />

5. Enter this command:
```
POST kbn://internal/kibana/settings
{
   "changes": {
      "agentBuilder:enabled": true
   }
}
```
6. Refresh the page and you should see an option for ***Agents*** in the sidebar

<img width="241" height="207" alt="Screenshot 2025-10-04 at 3 08 24 PM" src="https://github.com/user-attachments/assets/dc924680-cccd-4cbf-97b3-f667b503412c" />



   
