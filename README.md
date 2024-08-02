# TFF_Optimization
A tool to help make decisions for Telegraph Fantasy Football, following the Sky project: https://github.com/SamTroy/SkyFF_Optimization

Generates player expected points and transfer plan

Modifying player expected values and minutes (EV and xMins) or using other sources to reflect your own judgment is encouraged

## Setting up
- Install python
- Add highs and/or cbc to environment path
- Clone this repository to your machine
- Install all packages in the Imports section of the notebook

## Running the solver
- For xMins purposes it is recommended to download FPL Review projections from https://fplreview.com/ and save the file in data folder as "fplreview.csv". Alternatively, omit this step to use defaults or produce your own set of xMins
- Open the notebook and run import and function definition cells
- Run the commands at the bottom of the notebook for generation of EV and optimized transfer plans

### Acknowledgements and sources
- Team strength data used with permission from Elevenify: https://elevenify.substack.com/
- Other team and player data derived from publicly available statistics (primarily Opta) and market odds
- Inspiration and guidance for the solver framework from Sertalp: https://github.com/sertalpbilal/FPL-Optimization-Tools
- Continuous feedback and collaboration with members of the fantasy football analytics community

### Future plans
- Incorporate FA Cup games