[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=BigApple35)](https://github.com/anuraghazra/github-readme-stats)


- uses: Platane/snk@v3
  with:

    github_user_name: ${{ github.repository_owner }}

  
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9


  <picture>
  <source media="(prefers-color-scheme: dark)" srcset="github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="github-snake.svg" />
  <img alt="github-snake" src="github-snake.svg" />
</picture>
