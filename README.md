# Biohackathon Project Template

This repository is a starting point for a three-day team project. This repository is populated with a starting template for team organization and planning. Use it to plan, build, and document work. Please adjust this repository to suite the needs of your team.

> **Team leads:** Start with the [team lead checklist](project-management/README.md) before the event or during your first team meeting.

## Project Profile

- **Project name:** [Add a short, descriptive name]
- **Question, problem, or opportunity:** [What are you exploring?]
- **Data, inputs, or evidence:** [What will you use, and where does it come from?]
- **Expected output:** [What will you show, test, explain, or demonstrate?]
- **Tools and stack:** [Languages, libraries, notebooks, APIs, databases, services, or other tools]
- **Team lead:** [Name and GitHub handle]
- **Team members and roles:** [Link to `project-management/team.md`]
- **Communication:** [Add the agreed channel or contact]

Naming the tools and stack early helps the team lead create useful roles and divide work realistically. It is fine to revise this section as the project develops.

## Vision and Mission

- **Vision:** [Describe the change, insight, or capability you hope this project supports.]
- **Mission:** [Describe what the team will do during the biohackathon to move toward that vision.]

## About

[Add a short explanation of the motivation, background, and why the question or problem matters.]

## Roadmap and Milestones

| When | Focus | Expected outcome |
| --- | --- | --- |
| Day 1 | Agree on the question, inputs, stack, roles, and first tasks | A shared plan and a first small change in the repository |
| Day 2 | Build, test, and compare approaches | A working result or clear evidence about what does not work |
| Day 3 | Stabilize, document, and present | A demo or handoff with methods, limitations, and next steps |

The goal is not a perfect production system. The goal is a clear, honest, useful result that the team can explain and others can build on.

## Start Here

1. **Access your assigned team repository.** Organizers will provide the repository and add team members. Confirm that you can open it on GitHub and clone it to your computer. Follow [Git and GitHub basics](docs/git-github-basics.md) for the full path.
2. **Complete the project profile.** Agree on the question, inputs, expected output, tools, and team roles before pursuing a large implementation.
3. **Make a small first change.** Create a branch, update this README or document a data source, commit the change, and open a pull request. Use the terminal steps in [Git and GitHub basics](docs/git-github-basics.md) or [GitHub Desktop](https://desktop.github.com/) if you prefer a graphical interface.
4. **Ask for help early.** Record blockers in an issue, raise them at a check-in, or ask a mentor. See [troubleshooting](docs/troubleshooting.md) for common recovery steps.

## The Team

- **Members and roles:** Record these in [team.md](project-management/team.md).
- **Ways of working:** Use the [team lead checklist](project-management/README.md) to agree on branches, reviews, communication, and check-ins.
- **Current plan:** Keep small first tasks and risks in [project-plan.md](project-management/project-plan.md).

## Project Structure

Use the folders that fit your project. You do not need to fill every folder. The following is just a suggestion, yours might look different.

```text
data/raw/           Original inputs; do not edit in place
data/processed/     Cleaned or transformed data
models/             Models, predictions, or model notes
project-management/ Team plan, roles, decisions, and check-ins
src/                Reusable code, organized by purpose
docs/               Optional learning and troubleshooting guides
assets/             Images or other supporting project assets
```

## Data, meta data and secrets
**Do not commit passwords, API keys, private information, or identifiable human or clinical data. Check the source and license before sharing external data or media.**

## Resources

- New to Git or GitHub or need to know how to work with git in a shared repo: read [Git and GitHub basics](docs/git-github-basics.md).
- Using Copilot agents: read [AI assistance](docs/ai-guidance.md) and [Agent.md](Agent.md).
- Stuck during setup: open [troubleshooting](docs/troubleshooting.md).
- Collaborating on changes: see [contributing](CONTRIBUTING.md).

## Contributing to your team
### A Simple Workflow

1. Pick a small task or write down a blocker.
2. Create a branch with a clear name, such as `add-project-profile` or `fix-data-path`.
3. Make one focused change and commit it with a short message.
4. Push the branch and open a pull request.
5. Ask another teammate to look at the change before merging.
6. Update the README or project notes when the change affects how someone uses the project.

The [Git and GitHub basics](docs/git-github-basics.md) guide explains each step, including a GitHub Desktop workflow.

### A Pull Request Is Ready When

- The change has a clear purpose.
- A teammate can understand what changed.
- You have recorded how you checked it, or explained why checking was not possible.
- Relevant assumptions, data sources, and limitations are documented.
- The change does not include credentials or sensitive data.

Small, incomplete pull requests are welcome when they make the current state visible and clearly describe what remains.


## Reproducibility and Attribution

Make work easier to inspect and reuse by keeping inputs, decisions, methods, and limitations visible. Prefer small readable steps over unexplained one-off commands. Cite data, code, models, and external resources that your project depends on. These practices help the next person understand what happened.

This repository is a reusable template. See [LICENSE.md](LICENSE.md) for the licensing terms and update the project profile and attribution when you create a team project.

# Code of Conduct

In this repository, we use St. Jude's Code of Conduct document, outlining our expectations for all participants. Ask for help early, give feedback about the work rather than the person, and make room for different levels of experience.

For details, please visit: https://issuu.com/sjcrh/docs/st._jude_code_of_conduct.

