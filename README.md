<!--START_SECTION:waka-->
<!--END_SECTION:waka-->
name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.GH_TOKEN }}



[![Typing SVG](https://readme-typing-svg.herokuapp.com?size=32&duration=7000&color=134155&lines=Hi++there+%F0%9F%91%8B++Welcome%2C;My+Name+is+Ashkan!;A+PhD+student%2C;Happy+to+have+you+here!;Feel+free+for+reaching+out.;I+am+always+around+%F0%9F%98%8A;https%3A%2F%2Fashkan-pirmani.github.io)](https://ashkan-pirmani.github.io)


<div class="row">
<a href="">
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=ashkan-pirmani&count_private=true&&show_icons=true" />
</a>
<a href="">
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ashkan-pirmani&layout=compact&hide=javascript,html,CSS&langs_count=8" />
</a>
</div>


[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=ashkan-pirmani)](https://git.io/streak-stats)
