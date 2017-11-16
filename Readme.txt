1.put a .bat file in the folder script_run
	>>in order to create a  .bat file these are the steps:-
		>>first create a script that you need to run, for e.g. cmd /k "cd D:\mutual Bank\odoo-8.0 && D: && python odoo.py -w odoo -r odoo --addons-path=addons,mutual-erp-bank"
		>>then save the file as {file_name}.bat instead of just {file_name}.
		>>hence that is how you .bat file is created.
2.place the startup_server.bat file on desktop.
3.The startup_server.bat file is automatically configured to run file that are present in the location of the folder script_run.
4.prompt will open which will run each cmd by pressing enter.