# Global SkillPath RCE Source

Benign source repository for testing whether a GitHub skill folder path recorded during normal global install can later reach the Windows `skills update --global` shell sink.

The skill folder name intentionally contains Windows shell metacharacters that are valid path characters. The payload uses `copy NUL` to create an empty marker without requiring `>` in the repository path.
