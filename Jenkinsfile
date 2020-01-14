def UPSTREAM_PROJECTS_LIST = [ "Mule-runtime/mule-extensions-parent/1.1.x",
                               "Mule-runtime/mule-http-service/1.3.x",
                               "Mule-runtime/mule-oauth-service/1.1.x",
                               "Mule-runtime/mule-scheduler-service/1.1.x",
                               "Mule-runtime/mule-soap-service/1.1.x" ]

Map pipelineParams = [ "upstreamProjects" : UPSTREAM_PROJECTS_LIST.join(','),
                       "projectType" : "Runtime" ]

runtimeBuild(pipelineParams)
