postcommit-checker
==================
Simple script for checking commit message. It displays warning, if commit message doesn't match a defined pattern. Script might be used e.g. as a post-commit hook.

Configuration:
<ul>
  <li><b>MSG_REGEX</b> - pattern for commit message subject</li>
  <li><b>REPO_REGEX</b> - repository regular expression</li>
  <li><b>WARN_MESSAGE</b> - message displayed if commit message doesn't match a pattern</li>
</ul>