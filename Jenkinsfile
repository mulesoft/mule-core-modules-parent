def UPSTREAM_PROJECTS_LIST = [ "Mule-runtime/mule-extensions-parent/support/1.1.x",
                               "Mule-runtime/mule-http-service/support/1.3.x",
                               "Mule-runtime/mule-oauth-service/support/1.1.x",
                               "Mule-runtime/mule-scheduler-service/support/1.1.x",
                               "Mule-runtime/mule-soap-service/support/1.1.x" ]

Map pipelineParams = [ "upstreamProjects" : UPSTREAM_PROJECTS_LIST.join(','),
                       "projectType" : "Runtime" ]

runtimeBuild(pipelineParams)
