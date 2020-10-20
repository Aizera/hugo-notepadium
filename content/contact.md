+++
date = ""
tags = []
title = "Contact"
comments = false

+++
<style>
	/* Form */
	/*  
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
	*/
	
	label {
		color: #96a8b3;
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
		background-color : #222831;
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


/*style*/
  
	input, select, textarea {
    		font-family: "Source Sans Pro", Helvetica, sans-serif;
			font-size: 14pt;
			font-weight: 300;
			line-height: 2;
			letter-spacing: 0.2em;	
	}

	input[type="submit"],
	input[type="reset"],
	input[type="button"],
	button,
	
	.button {
		-moz-appearance: none;
		-webkit-appearance: none;
		-ms-appearance: none;
		appearance: none;
		-moz-transition: background-color 0.2s ease-in-out, border-color 0.2s ease-in-out, color 0.2s ease-in-out;
		-webkit-transition: background-color 0.2s ease-in-out, border-color 0.2s ease-in-out, color 0.2s ease-in-out;
		-ms-transition: background-color 0.2s ease-in-out, border-color 0.2s ease-in-out, color 0.2s ease-in-out;
		transition: background-color 0.2s ease-in-out, border-color 0.2s ease-in-out, color 0.2s ease-in-out;
		display: inline-block;
		height: 2.75em;
		line-height: 2.75em;
		padding: 0 1.5em;
		background-color: transparent;
		border-radius: 4px;
		border: solid 1px #c8cccf;
		color: #96a8b3 !important;
		cursor: pointer;
		text-align: center;
		text-decoration: none;
		white-space: nowrap;
	}

	input[type="submit"]:hover,
	input[type="reset"]:hover,
	input[type="button"]:hover,
	button:hover,
	.button:hover {
		border-color: #ff7496;
		color: #ff7496 !important;
	}

	input[type="submit"].icon,
	input[type="reset"].icon,
	input[type="button"].icon,
	button.icon,
	.button.icon {
		padding-left: 1.35em;
	}

	input[type="submit"].icon:before,
	input[type="reset"].icon:before,
	input[type="button"].icon:before,
	button.icon:before,
	.button.icon:before {
		margin-right: 0.5em;
	}

	input[type="submit"].fit,
	input[type="reset"].fit,
	input[type="button"].fit,
	button.fit,
	.button.fit {
		width: 100%;
	}

	input[type="submit"].small,
	input[type="reset"].small,
	input[type="button"].small,
	button.small,
	.button.small {
		font-size: 0.8em;
	}

	input[type="submit"].large,
	input[type="reset"].large,
	input[type="button"].large,
	button.large,
	.button.large {
		font-size: 1.35em;
	}

	input[type="submit"].disabled, input[type="submit"]:disabled,
	input[type="reset"].disabled,
	input[type="reset"]:disabled,
	input[type="button"].disabled,
	input[type="button"]:disabled,
	button.disabled,
	button:disabled,
	.button.disabled,
	.button:disabled {
		pointer-events: none;
		opacity: 0.5;
	}
</style>
    
<form name="Contact Aizera" method="POST" netlify-honeypot="bot-field" data-netlify="true"> 
<p> <label>NAME: <input type="text" name="NAME:" required></label>  
</p>

<p class="hidden">
    <label>AGE: <input name="bot-field" /></label>
  </p>

<p><label>EMAIL: <input type="email" name="Email:" required></label>  
</p>

<p>	<label>MESSAGE: <textarea name="Message:" required></textarea></label>
</p>

<p>
<button type="submit">SUBMIT</button>
</p>
</form>