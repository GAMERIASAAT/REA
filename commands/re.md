# Reverse Engineering Command

Analyze a binary or codebase for reverse engineering.

## Usage

```
/re <target> [options]
```

## Arguments

- `<target>` — File path, binary, or code snippet to analyze
- `[options]` — Optional flags: `--static`, `--dynamic`, `--deobfuscate`, `--vuln-research`

## Behavior

When invoked, the assistant will:

1. Identify the target type and architecture
2. Perform static analysis (strings, imports, sections)
3. Suggest deobfuscation steps if packed/encrypted
4. Highlight potential vulnerabilities or interesting code paths
5. Recommend tools and next steps

## Example

```
/re ./malware_sample.exe --static --deobfuscate
```

⚠️ Only analyze software you own or have explicit permission to test.