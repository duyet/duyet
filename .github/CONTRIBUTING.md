# Contributing to @duyet's Profile

First off, thank you for considering contributing! 🎉

This is a personal GitHub profile repository, but contributions are welcome for fixing typos, broken links, or suggesting improvements.

## How Can I Contribute?

### Reporting Bugs or Issues

If you find a broken link, typo, or any issue:

1. Check if the issue already exists in the [issue tracker](https://github.com/duyet/duyet/issues)
2. If not, [create a new issue](https://github.com/duyet/duyet/issues/new) with:
   - A clear, descriptive title
   - A description of the issue
   - Steps to reproduce (if applicable)
   - Screenshots (if applicable)

### Suggesting Enhancements

Have an idea to improve this profile? Great!

1. Check if the suggestion already exists in the [issue tracker](https://github.com/duyet/duyet/issues)
2. If not, create an issue describing:
   - The enhancement you'd like to see
   - Why it would be useful
   - Any examples or mockups (if applicable)

### Pull Requests

Pull requests are welcome! Here's how to submit one:

1. **Fork the repository** and create your branch from `main`

```bash
git clone https://github.com/YOUR-USERNAME/duyet.git
cd duyet
git checkout -b fix/my-fix
# or
git checkout -b feature/my-feature
```

2. **Make your changes**

   - Fix the issue or add the feature
   - Test your changes locally
   - Ensure all links work
   - Follow the existing code style

3. **Commit your changes**

```bash
git add .
git commit -m "fix: description of what you fixed"
# or
git commit -m "feat: description of what you added"
```

We follow [Conventional Commits](https://www.conventionalcommits.org/):

- `fix:` for bug fixes
- `feat:` for new features
- `docs:` for documentation changes
- `chore:` for maintenance tasks
- `style:` for formatting changes

4. **Push to your fork**

```bash
git push origin fix/my-fix
```

5. **Open a Pull Request**

   - Go to the [original repository](https://github.com/duyet/duyet)
   - Click "New Pull Request"
   - Select your fork and branch
   - Fill in the PR template with details about your changes
   - Link any related issues

### What to Contribute

Good first contributions:

- 🔗 Fix broken links
- ✍️ Fix typos or grammar
- 📝 Improve documentation
- 🎨 Suggest visual improvements
- 🐛 Report bugs in GitHub Actions workflows
- ⚡ Performance improvements

### What NOT to Contribute

Please don't:

- Change personal information (name, contact details, etc.) without discussion
- Add promotional content
- Make subjective styling changes without discussion
- Add unnecessary dependencies

## Development Guidelines

### Testing Links

Before submitting, ensure all links work:

```bash
# The link checker workflow will automatically run on PRs
# You can also manually test links using:
npx markdown-link-check README.md
```

### Markdown Style

- Use consistent heading levels
- Keep lines reasonably short for readability in raw markdown
- Use relative links for internal files
- Use absolute URLs for external links

### GitHub Actions

If you're modifying workflows:

- Test them in your fork first
- Pin action versions (don't use `@master` or `@main`)
- Add comments explaining non-obvious parts
- Follow the principle of least privilege for permissions

## Code of Conduct

This project follows the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## Questions?

Feel free to:

- Open an issue for discussion
- Reach out via [email](mailto:duyet@duyet.net)
- Connect on [LinkedIn](https://linkedin.com/in/duyet)
- Message on [Telegram](https://t.me/duyet)

## Recognition

All contributors will be recognized! Your contributions, no matter how small, are valued and appreciated. 🙏

---

Thank you for contributing! 🚀
