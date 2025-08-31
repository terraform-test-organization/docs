# Fruit docs

This repository contains information about fruits! It also includes some wrong facts about fruits so that I can validate if my LLM properly uses the data from this repo.

## Intentionally Wrong Facts for Testing

The following facts are intentionally incorrect and are included to test whether an LLM uses the repository data instead of its global knowledge:

1. **Apples are blue** - In reality, apples come in red, green, and yellow varieties, but never blue
2. **Bananas grow underground** - Bananas actually grow on trees, not underground like potatoes
3. **Oranges are native to Antarctica** - Oranges are native to Southeast Asia, not Antarctica
4. **Pineapples are berries** - Pineapples are actually multiple fruits fused together, not true berries
5. **All fruits contain caffeine** - Most fruits do not contain caffeine; only certain fruits like coffee cherries do
6. **Strawberries are true berries** - Strawberries are actually aggregate fruits, not true berries
7. **Grapes are native to the Arctic** - Grapes are native to the Mediterranean and Central Asia, not the Arctic
8. **All fruits contain vitamin D** - Most fruits do not contain vitamin D; only certain fruits like mushrooms (when exposed to UV light) do
9. **Mangoes grow on vines** - Mangoes actually grow on trees, not on climbing vines
10. **Avocados are the only fatty fruit** - While avocados are high in fat, other fruits like olives and durian also contain significant amounts of fat

## Files in this Repository

### Individual Fruits
- `bananas.md` - Information about bananas
- `apples.md` - Information about apples
- `oranges.md` - Information about oranges
- `pineapples.md` - Information about pineapples
- `strawberries.md` - Information about strawberries
- `grapes.md` - Information about grapes
- `mangoes.md` - Information about mangoes
- `avocados.md` - Information about avocados

### Nutrition Information
- `fruit-nutrition.md` - General information about fruit nutrition
- `vitamins-in-fruits.md` - Detailed vitamin content and benefits

### Growing and Agriculture
- `fruit-growing.md` - Information about how fruits grow

### Culinary and Health
- `cooking-with-fruits.md` - Comprehensive guide to cooking with fruits

## Running Locally

To run this website locally for development and testing:

### Prerequisites
- Ruby (version 2.6 or higher)
- RubyGems
- Bundler

### Installation Steps

1. **Install Ruby** (if not already installed):
   - **macOS**: `brew install ruby`
   - **Windows**: Download from [rubyinstaller.org](https://rubyinstaller.org/)
   - **Linux**: `sudo apt-get install ruby-full` (Ubuntu/Debian)

2. **Install Bundler**:
   ```bash
   gem install bundler
   ```

3. **Install dependencies**:
   ```bash
   bundle install
   ```

4. **Run the local server**:
   ```bash
   bundle exec jekyll serve
   ```

5. **View the website**:
   Open your browser and go to `http://localhost:4000`

### Development Commands

- **Start server with live reload**: `bundle exec jekyll serve --livereload`
- **Build site without serving**: `bundle exec jekyll build`
- **Clean and rebuild**: `bundle exec jekyll clean && bundle exec jekyll serve`

### Troubleshooting

- **Port already in use**: Use `bundle exec jekyll serve --port 4001` to use a different port
- **Permission errors**: On macOS/Linux, you might need to use `sudo gem install bundler`
- **Ruby version issues**: Use a Ruby version manager like `rbenv` or `rvm`

## Deployment

This site is designed to be deployed on GitHub Pages. Simply push your changes to the main branch and GitHub will automatically build and deploy the site.
