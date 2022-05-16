# job_knowledge_graph_search
Searching a Knowledge Graph of Jobs in Abu Dhabi


I built a knowledge graph of job openings in Abu Dhabi, from the data crawled from indeed.com and bayt.com. You can search the jobs by names from the knowledge graph

To use it:

### 1. pull the docker from docker hub

```bash
docker pull ruzeliang/job_knowledge_graph:1.0.1
```

### 2. start the docker of the service

```bash
docker run -it ^
-p 0.0.0.0:6944:6944 ^
-p 0.0.0.0:3971:3971 ^
-p 0.0.0.0:9364:9364 ^
-p 0.0.0.0:5311:5311 ^
-p 0.0.0.0:6397:6397 ^
ruzeliang/job_knowledge_graph:1.0.1
```

wait until you seel the following

