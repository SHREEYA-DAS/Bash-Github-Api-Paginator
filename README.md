<h1>GitHub API Pagination Handler</h1>

<p><strong>Description:</strong> This Bash script is a simple tool for interacting with the GitHub API and handling paginated responses. It is particularly useful when querying GitHub API endpoints that return multiple pages of data.</p>

<h2>Features:</h2>
<ul>
  <li>Authenticates with the GitHub API using a personal access token.</li>
  <li>Sends requests to specified GitHub API endpoints.</li>
  <li>Handles pagination by making multiple requests if necessary.</li>
  <li>Outputs the aggregated results to the console.</li>
</ul>

<h2>Usage:</h2>

```bash
./github_api_handler.sh [your-github-token] [github-api-endpoint]
```

<h2>Example:</h2>

```bash
./github_api_handler.sh myAccessToken /users/octocat/repos
```

<h2>Dependencies:</h2>
<ul>
  <li>Bash</li>
  <li>cURL</li>
</ul>
<p><strong>Note:</strong> Ensure that you have a valid GitHub token with the required permissions when using this script. Refer to the GitHub API documentation for more details.</p>
<h2>Contributing:</h2>
<p>Contributions are welcome! Feel free to open issues or submit pull requests.</p>
<h2>License:</h2>
<p>This project is licensed under the <a href="LICENSE">MIT License</a>.</p>

