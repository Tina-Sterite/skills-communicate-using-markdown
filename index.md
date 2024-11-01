# markdown header 1
## markdown header 2
### markdown header 3
#### markdown header 4
##### markdown header 5
###### markdown header 6

adding a commit message to the "bottom" of this file.. doesn't seem like the right place to put the message but anyway.. practiced markdown headers 1 through 6

![Image of Yogitocat](https://octodex.github.com/images/yogitocat.png)

```python
import os
from datetime import datetime
from dotenv import load_dotenv

# Load environment variables
load_dotenv()

# Set USER_AGENT environment variable if not already set
USER_AGENT = os.getenv("USER_AGENT")

#openai key
openai_api_key = os.getenv('OPENAI_API_KEY')
```
adding a task list
- [ ] this is a task list
- [ ] ooohh.. it adds new lines for you
- [ ] that's cool
- [ ] last item on my list
