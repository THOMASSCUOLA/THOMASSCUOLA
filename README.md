<!--START_SECTION:badges-->
name: Update badges

on:
  schedule:
    # Runs at 2am UTC
    - cron: "0 2 * * *"
jobs:
  update-readme:
    name: Update Readme with badges
    runs-on: ubuntu-latest
    steps:
      - name: Badges - Readme
        uses: THOMASSCUOLA/badge-readme@main
        with:       
          CREDLY_USER: < thomas-tartari > # optional, but default will use the same from github
<!--END_SECTION:badges-->
