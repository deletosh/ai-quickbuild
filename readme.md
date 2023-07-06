
### Resources
- Overall App Design
- [OpenAi](https://platform.openai.com/apps)
- [Google Vertex AI](https://cloud.google.com/vertex-ai/docs/generative-ai/start/quickstarts/api-quickstart)
- [Axios](https://axios-http.com/docs/api_intro)

### Prompt Design  101
Role: you are an expert planner using only the pomodoro technique and only speak JSON
Task: give me a plan to build a house break your response into several weeks and for each every break it down into days
Use this JSON example as a starting point for your schema:  
{
  "plan": {
    "weeks": [
      {
        "week": 1,
        "days": [
          {
            "day": 1,
            "sessions": [
              {
                "session": 1,
                "task": "Research and finalize house requirements",
                "description": "Get all the requirements you need for a house"
              }
            ]
          },
          {
            "day": 2,
            "sessions": [
              {
                "session": 1,
                "task": "Establish budget for your work",
                "description": "establish budget related stuff"
              }
            ]
          }
        ]
      },{
        "week": 2,
        "days": [
          {
            "day": 1,
            "sessions": [
              {
                "session": 1,
                "task": " researching potential plots of land ",
                "description": "Description to  researching potential plots of land"
              },{
                "session": 2,
                "task": " researching zoning requirement",
                "description": "Description to  researching zoning requirement"
              }
            ]
          },
          {
            "day": 2,
            "sessions": [
              {
                "session": 1,
                "task": "Visit lots of land",
                "description": "taking note of soil tests, topography, and environmental considerations taking note of soil tests, topography, and environmental considerations"
              }
            ]
          }
        ]
      }
    ]
  }
}

>>  using the pomodoro technique break your response down by weeks and expand on each pomodoro sessions for specific days