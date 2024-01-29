# Shopify's Standardized Product Taxonomy

Shopify's standardized and public product taxonomy used across our systems. Standardizes product categories, attributes, and attribute values.

## Organization

Organized into a few key folders, which are important to understand how to consume and contribute:

```
# Source (of truth) files to make PRs against
# DO NOT use this folder for integration
src/
  categories/
    aa_apparel_accessories.yml
    ...

# Distribution files for stable output. Do not modify directly.
# DO USE this folder for integration
dist/
  txt/
    categories.txt
    categories/
      aa_apparel_accessories.txt
      ...

# helper methods to generate dist
bin/
```

## Releases

Managed with releases on Github and generally follows [semver](https://semver.org/). Current version always found in [`VERSION`](./VERSION).

## License

Shopify's Product Taxonomy is released under the [MIT License](./LICENSE).
