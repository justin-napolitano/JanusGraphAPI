---
slug: github-janusgraphapi-note-technical-overview
id: github-janusgraphapi-note-technical-overview
title: JanusGraphAPI
repo: justin-napolitano/JanusGraphAPI
githubUrl: https://github.com/justin-napolitano/JanusGraphAPI
generatedAt: '2025-11-24T18:39:17.383Z'
source: github-auto
summary: >-
  This repo features Python scripts that bridge pandas with JanusGraph and
  Gremlin servers. It lets you create a demo database for every ZIP code in the
  US as a proof of concept.
tags: []
seoPrimaryKeyword: ''
seoSecondaryKeywords: []
seoOptimized: false
topicFamily: null
topicFamilyConfidence: null
kind: note
entryLayout: note
showInProjects: false
showInNotes: true
showInWriting: false
showInLogs: false
---

This repo features Python scripts that bridge pandas with JanusGraph and Gremlin servers. It lets you create a demo database for every ZIP code in the US as a proof of concept.

## Key Components

- **Python 3**: Core language.
- **JanusGraph & Gremlin Server**: Database backend.
- **pandas**: Data manipulation.
- **gremlin-python client**: For communicating with Gremlin.

## Quick Start

1. **Clone the Repo**:
    ```bash
    git clone https://github.com/justin-napolitano/JanusGraphAPI.git
    cd JanusGraphAPI
    pip install gremlinpython pandas
    ```

2. **Run Scripts**:
   - Prepare the ZIP code database:
     ```bash
     python PrepareZipCodeDB.py
     ```
   - Add the `is_root` property:
     ```bash
     python AddIsRootProperty.py
     ```

### Gotchas

- Ensure JanusGraph is running at `192.168.1.195:8182`.
- Some scripts might be placeholders, so keep an eye out for that.
