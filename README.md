# path_filtering_with_require_check
This sample shows how to return green status when you enabled `GitHub require status checks` on a specific job.

If `README.md` has been changed, `mapping-file-status` will be true in `continue-config.yml`.
If not, from the condition of `mapping-file-status`, it will execute another job that you configure.
(In this case, I recommend setting a blank step to return green status)

Please note that this configuration makes always runs a job.
