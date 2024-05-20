tequ-node-red-plotly-add
=====================

Plotly Dashboard 2.0 ui-template.

## Install

Run the following command in your Node-RED user directory - typically `~/.node-red`

        npm install Lapland-UAS-Tequ/tequ-node-red-plotly-add

## Information

Manages creation, adding data and clearing Plotly-chart.

- You have to create ui-template that holds plotly chart with 
unique id.
- You have to edit subflow.json file manually after installation and replace ui-base id on 
  flow -> ui-template and flow -> ui-base.


Example ui-template:

``
<template>
    <div id="plotly_chart"></div>
</template>
``

This node can manage creation and adding data to multiple plotly-charts.

