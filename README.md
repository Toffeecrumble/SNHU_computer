# CS 250 Portfolio: Sprint Review and Retrospective

**Author:** Mutia Aminu Jimbah  
**Course:** CS 250: Software Development Lifecycle, Southern New Hampshire University  
**Instructor:** Maryann Kupa

## What this repository contains

| File | Description |
|---|---|
| `SNHU_Travel_Sprint_Review_and_Retrospective.docx` | My final-project Sprint Review and Retrospective for the SNHU Travel pilot. Written as the Scrum Master, it reviews how the Product Owner, Scrum Master, Developer, and Tester roles worked together, how user stories were completed, how the team handled the detox and wellness pivot, and whether Scrum-Agile was the right approach. |
| `SNHU_Travel_Agile_Presentation.pptx` | The companion presentation for ChadaTech leadership, comparing Scrum-Agile with waterfall. |
| `README.md` | This file, with my reflections on the program's essential questions. |

Across the course I worked from all four SNHU Travel seats: Scrum Master, Product Owner, Tester, and Developer. The retrospective pulls those experiences together. The artifacts behind it include the focus-group user stories, the test cases and clarification emails, the Top Five Destination List, and the Top Detox Wellness Destinations Slide Show.

## Reflections

### How do I interpret user needs and implement them into a program? How does creating user stories help with this?

I interpret user needs by listening to the people who will use the product and then writing down what I heard in their words. As Product Owner, I ran a focus group with three loyal customers. One wanted a top-destinations list, one wanted it limited and filtered by price, and one wanted it personalized to her travel history and preferred vacation type. If I had guessed at priorities from inside the team, none of those needs would have reached the Product Backlog.

User stories keep a real person and a real reason attached to every piece of work. “As an end user, I want to click a link to view the top five destinations list, so that I can see the most popular locations” is much easier to build and test than a vague label like “improve recommendations.” The acceptance criteria under each story (an ordered list of five destinations, each with a name, a one-sentence description, a picture, and a link) became the developer’s build checklist and the tester’s pass/fail checks.

Stories are also deliberately incomplete. When I wrote test cases as the Tester, I found that the personalized list story never said how many destinations to show, whether a customer could pick more than one vacation type, or whether a price limit applied per person or per trip. I only found those gaps by trying to write a specific test step. A user story is therefore the start of a conversation with the Product Owner, not a replacement for one, and I learned to ask my questions in writing so the answers were recorded.

### How do I approach developing programs? What Agile processes do I hope to incorporate into my future development work?

I now approach development in small, checkable increments instead of one large build. I start from the acceptance criteria, build the smallest piece that satisfies them, test it, and show it to the Product Owner before moving on. Keeping content separate from navigation logic in my Slide Show paid off when the project pivoted to detox and wellness travel: only the title, five picture references, and five captions changed. I also learned to inspect the code before reacting to a change, because my first question (“do we have to scrap everything?”) turned out to be wrong.

In my future work I plan to keep these Agile practices:

- **Short, regular events:** a brief daily stand-up where blockers are raised immediately, a review with the people I am building for, and a retrospective that ends in concrete actions.
- **A clear Definition of Done and acceptance criteria written before building,** so “finished” is objective.
- **One shared board** for the backlog, test cases, and open questions. On SNHU Travel these lived in a spreadsheet, a test workbook, and email, so nobody saw them together. A tool such as Jira would have fixed that.
- **Testing the artifact I actually ship.** A picture failed to load in the exported JAR because of a file-name capitalization mismatch that did not show up when I ran the program in Eclipse. I now test the exported file as well as the development version.

### What does it mean to be a good team member in software development?

To me, a good team member makes the work visible and makes it easy for others to act. In practice that means writing clear, specific messages: questions that can be answered in a sentence, one section per recipient, a deadline tied to a team event, and a default assumption I will proceed with if I hear nothing, so the work does not stall. It also means raising blockers and bad news early, while they are still small, and telling teammates what I tested and where, instead of assuming they can guess what I missed.

It also means respecting each role’s decisions. As Developer, I proposed five wellness destinations but treated them as proposals for the Product Owner to approve, because content choices were hers to make. I also learned to ask before silently deciding something, such as leaving a caption color unchanged. A good team member in Scrum shares accountability: the Product Owner decides what matters, the Developer and Tester decide how to build and verify it, the Scrum Master keeps the process healthy, and everyone is honest about what is and is not done.

## AI usage acknowledgment

I used Anthropic’s Claude AI assistant to help draft this README, given a tight deadline. I provided the Module Eight guidelines, my Sprint Review and Retrospective, and my Module Three through Six journals and project files; Claude drafted the reflections from that work. I reviewed the text against my own experience on the SNHU Travel project.

## Reference

Anthropic. (2026). *Claude Sonnet 5.5* [Large language model]. https://www.anthropic.com/claude
