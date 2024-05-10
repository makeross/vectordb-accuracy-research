## Запуск в Docker qdrant:

*Unix/MacOS:*

`
docker run -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage qdrant/qdrant
`

Windows:

`
docker run -p 6333:6333 -v $PWD/qdrant_storage:/qdrant/storage qdrant/qdrant
`