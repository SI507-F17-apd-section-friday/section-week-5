# Section Week 5

### Part 1: Fetching, Caching, Extracting, Repeat

- [ ] Start with NYT Today's paper web page: http://www.nytimes.com/pages/todayspaper/index.html
- Code file: `frontpage.py`
- [ ] Extract data from the "Front Page" news articles including:
    - Title
    - Author(s)
    - Date
    - Summary
    - Thumbnail
- What data structure will you save this extracted data in? Class / Dictionary / List / List of Dictionaries?
- For each Front Page article
    - [ ] Get (and cache) that article's web page
    - [ ] Extract its related coverage of articles, and
    - [ ] Save its title, thumbnail, date, and link (What data structure will you use? Where will you save it?)

### Part 2: Making Milestones and Issues for Project 3

Carefully read through the `README.md` and the `# comments` in the code file, and break down what you have to do into milestones, issues and distinct tasks / sub-tasks

- Part 0: `_________` [200 points]
    - Get web page: `_________`
    - Extract `_______` attribute for all images in that page
        - [ ] Print the `_________` for these images
        - [ ] If missing, print `_________________`
        - [ ] Confirm output by comparing it with: `_______`
        - Note: no tests for this part
- Part 1: `_________` [100 points]
    - Get from cache: `_________`
        - [ ] How?
    - Create `_________` instance from the html
    - Extract links to pages of states `_________, _________, _________`
        - [ ] How will you go about doing this?
    - Get from cache: `_________`, and repeat it for `_________`
        - [ ] How will you go about doing this?
    - NOTE: Something to think about: You will be using what you just extracted and what you will write in Part 2, in Part 3.
- Part 2: `_________` [400 points]
    - class `_________`
        - What does it represent?
        - Constructor
            - [ ] What are the arguments?
            - [ ] What variables do you need to initialize?
            - [ ] How will you get the value to initialize each of them?
            - [ ] `self._______` / To extract, use `______._________("______")`
    - Method: `_________`
        - What are the arguments?
        - What should it return?
        - How will you approach this?
    - Method: `_________`
        - What are the arguments?
        - What should it return?
        - How will you approach this?
    - Method: `_________`
        - What are the arguments?
        - What should it return?
        - How will you approach this?
    - Test the class using `_____________`
- Part 3: `_________` [200 points]
    - Create: `_________`
        - How will you approach this?
    - Write: `_________`
        - [ ] Content: `_________`
        - [ ] Handle `_________`
        - How will you approach this?
- Submission [100 points]
    - Files to be included
        - [ ] All `.html` files used for caching
        - [ ] `_________`
        - [ ] `_________`
        - [ ] `_________`
        - [ ] More?

### Part 3: Some BeautifulSoup fun!

Let's try using BeautifulSoup on https://www.lingscars.com/ (please use caching! ProTip: Have a function that does this, which you can reuse in your assignment.)

- Extract the Menu
- Extract the names of all cars sold at Lings Cars, grouped by Brand Name (What data structure will you use?)
- Extract deals featured on home page
    - Car's picture
    - Name
    - Description
    - Type of Engine, Gearbox, Paint
    - Rent per month
    - Extract the number of visitors now and number of visitors today
- Having fun? Extract more information that you think is interesting.
