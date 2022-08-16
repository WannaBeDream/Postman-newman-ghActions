## Postman + newman + github actions (Pet store template)

1. Read: 
- <a href="https://svitla.com/blog/testing-rest-api-with-postman-and-curl"> Postman & Curl & REST article </a> 
- <a href="https://learning.postman.com/docs/writing-scripts/script-references/test-examples/">Postman tests examples (off doc)</a>
2. Upload `petstore.collection.json` in Postman app.  
3. Make some integration tests for pet model in Postman(could be status code/JSON check and so on).
4. Save new collection with your new integration tests with the same name as `petstore.collection.json`
5. Push to you github repo in main branch
6. Add Github action to run your tests in Github cloud by <a href="https://www.linkedin.com/pulse/running-postman-collections-via-github-action-nirmala-jayasanka"> article </a>
6. Check github actions for result