# Images Directory

This directory contains all images used in the What The Duck documentation.

## Organization

Images are organized to support the documentation pages:

- **General images**: Place shared images (logos, icons, etc.) directly in this folder
- **Page-specific images**: Consider organizing by topic or page name for larger collections

## Naming Conventions

To maintain consistency and clarity:

- Use lowercase with hyphens: `duck-programming-flow.png`
- Be descriptive: `what-the-duck-process-diagram.svg`
- Include page reference if specific: `duck-programming-example-1.png`

## Supported Formats

- **PNG**: For screenshots, diagrams with transparency
- **JPG/JPEG**: For photos or images without transparency
- **SVG**: For vector graphics, logos, and scalable diagrams (preferred when possible)
- **GIF**: For simple animations or demonstrations

## Usage in Markdown

Reference images using relative paths from the documentation file:

```markdown
![Alt text](images/your-image-name.png)
```

For images with captions:

```markdown
![Duck Programming Process](images/duck-programming-flow.png)
*Figure 1: The Duck Programming workflow*
```

## Best Practices

- Optimize images before committing (compress to reduce file size)
- Use descriptive alt text for accessibility
- Keep image files under 1MB when possible
- Use SVG for diagrams and illustrations when feasible
- Maintain aspect ratios appropriate for documentation
