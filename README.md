# rrd_grafana
Build a grafana dashboard using RRD fiiles


## Possible ways
1. Convert to JSON
  - convert .rrd to .json within rrdtool xport [usefull link1](https://stackoverflow.com/questions/18109244/converter-rrd-to-json)
  - convert .rrd to .json within python script [usefull link2](https://stackoverflow.com/questions/15286169/convert-rrd-file-to-json-in-python)
  - convert .rrd to .json within NodeJS [usefull link3](https://github.com/WernerBlake/RRDjs)
1. Use grafana RRD server
  - by Doublemarket [usefull link4](https://github.com/doublemarket/grafana-rrd-server)
  - by Andrew [usefull link5](https://github.com/andrewchambers/grafana-rrd-datasource)
  - [rrd server options](https://community.librenms.org/t/grafana-graphing-directly-from-rrds/6699/3)
  - [rrd server step by step](https://qiita.com/atfujiwara/items/58cda0dbe44b1e03ac7f)
1. Using [Graphite](http://graphiteapp.org sup)
