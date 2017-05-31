"# codeigniter_bootstrap" 

# Codeigniter + Bootstrap

Small framework ready to deploy

# How to Use bootstrap

Insert on section
```
<head>
	...
	<link rel="stylesheet" href="<?php echo base_url("assets/css/bootstrap.css"); ?>" />
	...
</head>
```
and insert befor close body tag
```
<body>	
	...
	<script type="text/javascript" src="<?php echo base_url("assets/js/jQuery-1.10.2.js"); ?>"></script>
	<script type="text/javascript" src="<?php echo base_url("assets/js/bootstrap.js"); ?>"></script>
</body>
```
respect the order, first jquery then bootstrap
