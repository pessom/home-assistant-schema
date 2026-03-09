# Home Assistant JSON Schemas

Automated JSON schema definitions for Home Assistant configuration files.
These schemas are generated directly from the official `vscode-home-assistant` extension,
ensuring compatibility with the latest Home Assistant releases.

## Features
- **Auto-validation:** Real-time syntax checking in your IDE.
- **Auto-completion:** Intelligence-based suggestions for keys and values.
- **Up-to-date:** Generated via CI/CD pipelines from official sources.

## Usage

### PyCharm / IntelliJ IDEA
1. Go to **Settings** > **Languages & Frameworks** > **JSON Schema Mappings**.
2. Click **+** to add a new mapping.
3. **Name:** `Home Assistant Configuration`
4. **Schema file or URL:** Use the latest release URL:
   `https://github.com/pessom/home-assistant-schema/releases/latest/download/configuration.json`
5. **File pattern:** `**/configuration.yaml`

## Releases

Specific versions corresponding to Home Assistant releases are available in the [Releases section](https://github.com/pessom/home-assistant-schema/releases).


## CI/CD Pipeline

The schemas are automatically updated and published using GitHub Actions. To trigger a manual update for a specific version, use the Update Home Assistant Schemas workflow and provide the desired tag from the [vscode-home-assistant](https://github.com/keesschollaart81/vscode-home-assistant) repository.

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.