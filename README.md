# Echo-E2E
## Usage
1. Run initial_setup.py to create model file (already saved in model folder using GPU)
2. Run server.py to start server that will return percentages by accepting post requests from user
### Post request example
curl -X POST  -F "survey_input= enter user response here" http://127.0.0.1:5000/result
