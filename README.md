


https://cadenceworkflow.io/docs/cli/

http://localhost:8088/domains

alias cadence="docker run --rm ubercadence/cli:master --address host.docker.internal:7933 "
cadence --domain samples-domain domain register
cadence --domain samples-domain domain describe
cadence --domain samples-domain workflow list
cadence --domain samples-domain workflow start -wt test-workflow -tl test-task-list -et 1000

cadence --domain samples-domain workflow list -op
cadence --domain samples-domain workflow terminate -wid 3f6d7e68-18b5-4dc4-a779-adacafaca60f


Temporal

    https://stackoverflow.com/questions/61157400/temporal-workflow-vs-cadence-workflow
