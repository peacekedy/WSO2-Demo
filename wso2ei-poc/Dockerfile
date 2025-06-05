FROM wso2/wso2ei-integrator:6.6.0

COPY HelloWorldAPI.xml /home/wso2carbon/wso2ei-6.6.0/repository/deployment/server/synapse-configs/default/api/
COPY deployment.toml /home/wso2carbon/wso2ei-6.6.0/conf/

EXPOSE 8280 8243

CMD ["/home/wso2carbon/wso2ei-6.6.0/bin/integrator.sh"]
