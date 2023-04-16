# linkedin-based-letters
Creating proposal letters based on LinkedIn profiles with ChatGPT

## Scraping
Scraped 5 LinkedIn profiles using Nubela's **proxyurl API**.  
Included only basic information and a list of email addresses, brought by the API from external sources.  
Saved backup copies on Google Drive in *.json* format.  

## Information
Put together a universal prompt that includes essential data from the profile.  
It includes person's:
- full name 
- email (only the first one in the list)
- current occupation
- profile's headline
- person's profile summary
- years of experience, counting from the first day of the first job to today
- experiences in the following format: *[Title in company1; title in company2, ...]*
- education in the following format: *[Degree_name from school1, described as description; ...]*  

## Generation
Using OpenAI's API, generated letters with **ChatGPT-3.5's assistant mode**.  
Prompt included the aforementioned information and a task to create a proposal letter.  
