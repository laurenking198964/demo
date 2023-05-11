# demo
demo
# mtask任务区域，既不属于own脚本，也不属于jd_scripts脚本的，请使用mtask命令。


# 需自行将脚本放在scripts文件夹下，mtask命令运行的脚本可以以jd_、jr_、jx_开头，如
# 8 5 * * * mtask jd_live.js


# otask任务区域，AutoAddOwnCron=true时，自动识别脚本中的cron信息，无法保证准确，建议收到通知后主动检查。
# 在启动自用own脚本的cron任务时，程序会自动将文件复制到scripts文件夹下，然后再运行。
# 自用own任务开始，请不要增加、删除或修改本行任何字符（包括空格及#），这是给自动化程序识别用的。
