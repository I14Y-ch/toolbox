# I14Y Toolbox

The I14Y Toolbox serves as a centralized hub for accessing a variety of tools designed to streamline I14Y operations. Each tile on the main page links to a specific tool, offering specialized functionality. Changes to this repository are automatically deployed to [GitHub Pages](https://i14y-ch.github.io/toolbox/) via a GitHub Action.

## Available Tools

- **Concept Import Tool**: Import concepts from a spreadsheet table to the interoperability platform I14Y. [Open tool](https://concept-input.toolbox.i14y.c.bfs.admin.ch/) | [GitHub Repository](https://github.com/I14Y-ch/toolbox_concept_input)
- **Excel Upload Tool**: Upload and process Excel files to extract metadata and upload it to I14Y. [Open tool](https://excel-upload.toolbox.i14y.c.bfs.admin.ch/) | [GitHub Repository](https://github.com/I14Y-ch/excel_upload)
- **Harmonization Graph**: Explore where concepts are reused across I14Y dataset descriptions, data elements, and structures. [Open tool](https://harmgraph.toolbox.i14y.c.bfs.admin.ch/) | [GitHub Repository](https://github.com/I14Y-ch/harmgraph)
- **Keyword Generator**: Create keywords to enhance your dataset descriptions on I14Y. [Open tool](https://keyword-generator.toolbox.i14y.c.bfs.admin.ch/) | [GitHub Repository](https://github.com/I14Y-ch/keyword_generator)
- **SHACL Generator**: Generate the description of a data structure in the SHACL format for upload to I14Y. [Open tool](https://shacl.toolbox.i14y.c.bfs.admin.ch/) | [GitHub Repository](https://github.com/I14Y-ch/toolbox_shacl)
- **Data Structure Editor**: Manually describe a data structure or edit an existing structure. [Open tool](https://structure-generator.toolbox.i14y.c.bfs.admin.ch/) | [GitHub Repository](https://github.com/I14Y-ch/structure_generator)
- **Swagger2I14Y Import Tool**: Use your technical API specification (Swagger) to generate an API description on I14Y. [Open tool](https://swagger2dcat.toolbox.i14y.c.bfs.admin.ch/) | [GitHub Repository](https://github.com/I14Y-ch/swagger2dcat)

## Development

This is a simple HTML/CSS site hosted on GitHub Pages.

### Adding New Tools

To add a new tool to the toolbox:

1. Open `index.html`
2. Copy an existing tool card in the `.tools-grid` section
3. Update the link, image, title, and description
4. Commit and push the changes to automatically deploy

## Deployment

The site automatically deploys to GitHub Pages when changes are pushed to the main branch.
