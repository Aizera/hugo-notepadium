+++
date = ""
tags = []
title = "Contact"

+++
<style>
  	/* Form */
  		form {
		margin: 0 0 1.5em 0;
	}

		form > :last-child {
			margin-bottom: 0;
		}

		form > .fields {
			display: -moz-flex;
			display: -webkit-flex;
			display: -ms-flex;
			display: flex;
			-moz-flex-wrap: wrap;
			-webkit-flex-wrap: wrap;
			-ms-flex-wrap: wrap;
			flex-wrap: wrap;
			width: calc(100% + 2.25em);
			margin: -1.125em 0 1.5em -1.125em;
		}

			form > .fields > .field {
				-moz-flex-grow: 0;
				-webkit-flex-grow: 0;
				-ms-flex-grow: 0;
				flex-grow: 0;
				-moz-flex-shrink: 0;
				-webkit-flex-shrink: 0;
				-ms-flex-shrink: 0;
				flex-shrink: 0;
				padding: 1.125em 0 0 1.125em;
				width: calc(100% - 1.125em);
			}

				form > .fields > .field.half {
					width: calc(50% - 0.5625em);
				}

				form > .fields > .field.third {
					width: calc(100%/3 - 0.375em);
				}

				form > .fields > .field.quarter {
					width: calc(25% - 0.28125em);
				}

		@media screen and (max-width: 480px) {

			form > .fields {
				width: calc(100% + 2.25em);
				margin: -1.125em 0 1.5em -1.125em;
			}

				form > .fields > .field {
					padding: 1.125em 0 0 1.125em;
					width: calc(100% - 1.125em);
				}

					form > .fields > .field.half {
						width: calc(100% - 1.125em);
					}

					form > .fields > .field.third {
						width: calc(100% - 1.125em);
					}

					form > .fields > .field.quarter {
						width: calc(100% - 1.125em);
					}

		}

	label {
		color: #313f47;
		display: block;
		font-size: 0.9em;
		margin: 0 0 0.75em 0;
	}

	input[type="text"],
	input[type="password"],
	input[type="email"],
	input[type="tel"],
	select,
	textarea {
		-moz-appearance: none;
		-webkit-appearance: none;
		-ms-appearance: none;
		appearance: none;
		border-radius: 4px;
		border: solid 1px #c8cccf;
		color: inherit;
		display: block;
		outline: 0;
		padding: 0 1em;
		text-decoration: none;
		width: 100%;
	}

		input[type="text"]:invalid,
		input[type="password"]:invalid,
		input[type="email"]:invalid,
		input[type="tel"]:invalid,
		select:invalid,
		textarea:invalid {
			box-shadow: none;
		}

		input[type="text"]:focus,
		input[type="password"]:focus,
		input[type="email"]:focus,
		input[type="tel"]:focus,
		select:focus,
		textarea:focus {
			border-color: #ff7496;
		}
  
  
    /* STYLE */   
    body, input, select, textarea {
		color: #414f57;
		font-family: "Source Sans Pro", Helvetica, sans-serif;
		font-size: 14pt;
		font-weight: 300;
		line-height: 2;
		letter-spacing: 0.2em;
		text-transform: uppercase;
	}  
	button {
	width: 100%;
	padding: 10px;
	margin-top: 20px;
	border-radius: 20px;
	border: none;
	border-bottom: 4px solid #3e4f24;
	background: #5a7233; 
	font-size: 16px;
	font-weight: 400;
	color: #fff;
	}
	button:hover {
	background: #3e4f24;
	} 
</style>
    
<form name="Contact Aizera" method="POST" netlify> <p> <label>Name: <input type="text" name="Name:" required></label>  
</p>
<p>
<label>IGN: <input type="text" name="IGN:" required></label>  
</p>
<p>
<label>Discord Tag (Name#0000): <input type="text" name="Discord:" required></label>
</p>
<p>	<label>Message (Optional): <textarea name="message"></textarea></label>
</p>
<p>
<button type="submit">SUBMIT</button>
</p>
</form>