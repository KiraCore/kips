## How to Submit a KIP ? 

### Create your KIP markdown file following these requirements:

- An **Abstract** paragraph, summarizing the proposal. This paragraph must provide a clear understanding of what the KIP is about.
- A **Motivation** paragraph detailing the motivation behind this KIP. Explain why this KIP is necessary or beneficial for the community or project.
- **Concept and Implementation** description paragraph. The main content section of your KIP. Provide a comprehensive description of the changes or enhancements you are proposing. Include any relevant details, data, examples, or analyses that support your proposal. This section should be detailed to provide a clear and complete understanding of your KIP to the reviewers and community members.

### Submit your KIP by raising a PR to master:

1. Clone the repository:
```bash
git clone https://github.com/KiraCore/kips.git
cd kips
git fetch --all
git pull
```

2. Create a submission branch with a short name using hyphens (do not number your KIP):
```bash
git branch submission/short-name-of-your-kip
git checkout submission/short-name-of-your-kip
```

3. Add your file to the `kips` folder (do not number your file) and commit:

```bash
cp path/to/file kips/
git add .
git commit -m "your message"
git push
```

You can now raise a [Pull Request](https://github.com/KiraCore/kips/compare/PULL_REQUEST?template=PULL_REQUEST_TEMPLATE.md) and fill in the required form to submit your KIP.

## Contributors

<a align="center" href="https://github.com/KiraCore/kips/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=KiraCore/kips" />
</a>