# Jira_GroupBy
Groups JIRA issues in the various sprints in a backlog by assignee

If you're looking for a way to group tasks assigned to you in JIRA, you've come to the right place! JIRA GroupBy is a chrome extension that groups issues in the various sprints in a backlog by assignee. Simple click on the extension when you're in the Jira backlog page to group your issues!

JIRA GroupBy was created to solve the lack of a group by in the backlog page. The following points discuss it's behavior:
1. JIRA GroupBy only works when the URL is of the form: `.*atlassian\.net\/jira\/software\/c\/projects\/.*\/boards\/.*\/backlog`. If you have a different URL that you would like to try JIRA GroupBy on, please get in touch at lensdiff@gmail.com.
2. JIRA GroupBy works on the divs in the DOM directly. It starts by figuring out the assignees in the different sprints and then reorders the issues by grouping them together. This means the grouped issues are only visible to you on your browser i.e. if you refresh the page, the grouping will be lost.
3. JIRA GroupBy listens to changes in the UI and re-groups issues when it detects changes such as modifying assignees or story points from the backlog page.
4. If you have feature requests, feel free to email me at lensdiff@gmail.com.


If you find the extension useful, consider donating to me so I can keep up with JIRA changes and implement new feature requests :)
