FROM grafana/grafana

RUN grafana cli --pluginsDir "${GF_PATHS_PLUGINS}" plugins install grafana-clock-panel
RUN grafana cli --pluginsDir "${GF_PATHS_PLUGINS}" plugins install grafana-simple-json-datasource

ENTRYPOINT ["/run.sh"]