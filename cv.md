# **Curriculum vitae**
---
## Personal information
**First name:** Eugene
**Last name:** Romanov
**Address:** Tver, Russia
**Telephone:** +7-996-347-20-45
**Email:** nm5reimu@gmail.com
**Date of birth:** 10th June 1998
**Nationality:** Russian

---

## Brief  information 
**About:** I'm a young and smart guy who wants to work _(not sure)_ and make money.
**Goal:**
  - Studying front-end development
  - Get a job in EPAM

**Strengths:**
  - Fast learner
  - Enthusiasm for programming
  - Desire to learn
  - Not stupid

---

## Skills
**Basic skills:**
  - C
  - C#
  - JavaScript
  - CSS
  - HTML
  - React
  - Vue
  - Git
  - Markdown

---

## Example code


```
//Not very good code that no one will understand I guess

const showVideosInRows = (numberOfVideosInRow) => {        
        const rows = [...Array(Math.ceil((this.state.title.video.length) / numberOfVideosInRow))];
        const itemRows = rows.map( (row, idx) => 
            this.state.title.video.slice(idx * numberOfVideosInRow, idx * numberOfVideosInRow + numberOfVideosInRow)
        );
        const videoRows = itemRows.map((row, idx) => (
            <Grid.Row key={idx}>                    
                {
                    row.map((item, index) => (                        
                        <Grid.Column key={index}>
                            <Embed
                                icon='play'
                                placeholder={item.placeholder}
                                url={item.video_path}
                                active={false}
                                onClick={(e) => this.handleVideoDimmerChange(e, item.video_path)}
                            />
                            <h4>Part {item.part}</h4>
                        </Grid.Column>
                    ))
                }                                     
            </Grid.Row>
        )); 
        return videoRows;
    }  
```

---

## Work experience
Several **almost** finished C# and React/C# (React - front-end, C# - back-end) projects that no one should see. 

---

## Education
   - Tver State Technical University, Faculty of Information Technology, Bachelor of Software Engineering (2016 - 2020).
   - Accenture front-end courses.

---

## English language
**B1** Intermediate level.