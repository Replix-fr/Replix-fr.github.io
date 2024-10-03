# Replix-fr.github.io


<!DOCTYPE html>

<html style="font-size: 100%;">
	<head>
		<!--[if IE]><link rel="shortcut icon" href="/favicon.ico"><![endif]-->
		<meta name="msapplication-TileImage" content="/content/images/logo.png">
		<link rel="icon" href="/content/images/icon_24.png">
		<meta charset="utf-8" />
		<title>C# Online Compiler | .NET Fiddle</title>
		
	<link href="//netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.min.css" rel="stylesheet">
	

		<meta name="keywords" content=".NET, DotNet, C#, VB.NET, F#, CSharp, VbNet, FSharp, SandBox, Visual Studio, Fiddle, Code Snippet" />
		<meta name="description" content="Test your C# code online with .NET Fiddle code editor." />
		<meta name="viewport" content="width=device-width,maximum-scale=1,initial-scale=1,user-scalable=0">
		
	<link href="/Content/packages/bootstrap-3.0.2/css/bootstrap.min.css?v=2" rel="stylesheet"/>

	<link href="/content/css/desktop?v=qeETA7M4VrrYiioZRLhrsY1FysAfo1nqbV6Rpr9e79s1" rel="stylesheet"/>


	<style type="text/css">
		.ui-menu {
			display: inline-block;
			position: absolute;
			top: 360px;
			left: 15px;
			max-width: 350px;
			z-index: 1000;
		}

		.tab-content {
			padding-top: 40px;
		}

		.container {
			padding-top: 15px;
		}

		.vcenter {
			display: inline-block;
			vertical-align: middle;
			float: none;
			margin-right: -4px;
		}

		.vtop {
			display: inline-block;
			vertical-align: top;
			/*margin-top: 20px;*/
			float: none;
			margin-right: -4px;
		}

        #login-modal .modal-body > a {
            font-size: 17px;
            color: #333;
            width: 100%;
            display: block;
            text-align: center;
            border: 1px solid #efefef;
            border-radius: 10px;
            padding: 5px;
            background: #f7f7f7;
            margin-bottom: 5px
        }
		
        #login-modal .modal-body > a:hover {
            color: #0077CF;
            transition: .3s
        }

        .welly {
            background-color: #f7f7f7;
            border-radius: 10px;
            border: 1px solid #efefef;
            margin-top: 5px;
            padding: 9px
        }

        .access-type-container button {
            text-align: left;
        }
        .share-link {
            margin-top: 6px;
            margin-bottom: 10px;
        }
        .share-widget-output {
            margin-top: 6px;
        }

		.brand-logo {
			margin: 0;
			margin-top: 1px;
		}

	</style>
	
	
	<link href="/bundles/codemirrorcss?v=a3BXkN-CPs0uir7jXyTovklTyOV7sImo2wgaeho3aRo1" rel="stylesheet"/>

	
	<link href="/content/css/csharpcolors.css" rel="stylesheet"/>


	


	</head>
<body>
	<div class="container">
		




		<div class="modal fade" id="login-modal" tabindex="-1" role="dialog" aria-labelledby="login-modal-label" aria-hidden="true">
			<div class="modal-dialog" style="width: 400px;">
				<div class="modal-content">
					<div class="modal-header">
						<button type="button" class="close" data-dismiss="modal" aria-hidden="true">&times;</button>
						<h4 class="modal-title" id="login-modal-label">Log in</h4>
					</div>
					<div class="modal-body">
						<span class="danger" id="login-message"></span>
						<a href="/Account/LogIn?loginType=3" class="remote-login" data-type="3" rel="nofollow">
	<i class="fa fa-twitter"></i>
	Twitter
</a>
<a href="/Account/LogIn?loginType=2" class="remote-login" data-type="2" rel="nofollow">
	<i class="fa fa-envelope-o"></i>
	Gmail
</a>
<a href="/Account/LogIn?loginType=1" class="remote-login" data-type="1" rel="nofollow">
	<i class="fa fa-facebook-square"></i>
	Facebook
</a>
<br />
<div class="welly">
	<span style="font-size: 17px; width:100%;text-align: center;display: inline-block;">
		<i class="dnf-icon"> </i><a href="https://dotnetfiddle.net/" target="_blank">.NET Fiddle</a> and <i class="dna-icon"> </i><a href="https://dotnetcademy.net/" target="_blank">.NET Academy</a><br/> shared account
	</span>
<form action="/Account/LocalLogin" data-ajax="true" data-ajax-begin="loginRequest" data-ajax-method="POST" data-ajax-success="loginResponse" id="form0" method="post">		<div class="form-group">
			<input class="form-control" data-val="true" data-val-email="Invalid email format." data-val-required="The Email field is required." id="Email" name="Email" placeholder="Email" type="text" value="" />
			<span class="field-validation-valid" data-valmsg-for="Email" data-valmsg-replace="true"></span>
		</div>
		<div class="form-group">
			<input class="form-control" data-val="true" data-val-required="The Password field is required." id="Password" name="Password" placeholder="Password" type="password" />
			<span class="field-validation-valid" data-valmsg-for="Password" data-valmsg-replace="true"></span>
		</div>
		<div class="row form-group" style="padding-top: 0;">
			<div class="col-lg-7 col-md-7 col-sm-7 col-xs-7">
				<div class="checkbox">
					<label>
						<input data-val="true" data-val-required="The Remember me field is required." id="RememberMe" name="RememberMe" type="checkbox" value="true" /><input name="RememberMe" type="hidden" value="false" /> Remember me
						<span class="field-validation-valid" data-valmsg-for="RememberMe" data-valmsg-replace="true"></span>
					</label>
				</div>
			</div>
			<div class="col-lg-5 col-md-5 col-sm-5 col-xs-5 text-right">
				<button type="submit" class="btn btn-default" data-loading-text="Logging in...">Log in</button>
			</div>
		</div>
</form></div>

						<div class="row text-center">
							<a href="/SignUp">Sign up</a>&nbsp;or&nbsp;<a href="/PasswordReset" rel="nofollow">Reset password</a>	
						</div>
					</div>
				</div>
			</div>
		</div>

<div class="navbar navbar-default navbar-fixed-top" id="top-navbar">
	<div class="navbar-left-container hidden-xs hidden-sm hidden-md">
		<h1 class="brand-logo"><a href="/" class="logo navbar-brand"><img src="/content/images/logo.png" alt=".NET Fiddle"/></a></h1>
	</div>
	<div class="navbar-center-container">
				<div class="btn-group navbar-btn">
					<a class="btn btn-default" href="/">
						<span class="glyphicon glyphicon-chevron-left"></span> Back To Editor
					</a>
				</div>

	<div class="navbar-center-container">
		<div class="btn-group navbar-btn">
			<button class="btn btn-default" id="new-button" type="button">
					<span class="glyphicon glyphicon-file"></span> New
				</button>
				<button class="btn btn-default" id="save-button" data-loading-text="Saving..." type="button">
					<span class="glyphicon glyphicon-floppy-disk"></span> Save
				</button>
				<button class="btn btn-default" id="fork-button" data-loading-text="Forking..." type="button">
					<span class="glyphicon glyphicon-random"></span> Fork
				</button>
			</div>&nbsp;&nbsp;&nbsp;&nbsp;
			<div class="btn-group navbar-btn">
				<button class="btn btn-default" id="run-button" type="button">
					<span class="glyphicon glyphicon-play"></span> Run
				</button>
			</div>&nbsp;&nbsp;&nbsp;&nbsp;
			<div class="btn-group navbar-btn">
				<button class="btn btn-default" id="Share"  type="button">
					<span class="glyphicon glyphicon-share"></span> Share
				</button>
				<button class="btn btn-default" type="button" onclick="collaboration.init(); TogetherJS(this); return false;" value="Collaborate" id="togetherjs">
					<span class="glyphicon glyphicon-user"></span> Collaborate
				</button>
			</div>&nbsp;&nbsp;&nbsp;&nbsp;
			<div class="btn-group navbar-btn btn-tidyup">
				<a href="#" class="btn btn-default" id="tidyup-button">
					<span class="glyphicon glyphicon-check"></span> Tidy Up
				</a>
				<button class="btn btn-default dropdown-toggle" data-toggle="dropdown" id="tidyup-extra">
					 <span class="caret"></span>
				</button>
				<ul id="tidyup-menu" class="dropdown-menu">
					<li><a href="#" id="convert-button" target="_blank"></a></li>
					<li><a href="#" id="viewil-button"><span class="glyphicon glyphicon-flash"></span> View IL</a></li>
				</ul>
			</div>&nbsp;&nbsp;&nbsp;&nbsp;
		<div class="btn-group navbar-btn">
			<a class="btn btn-default" type="button" href="/GettingStarted/">
				<span class="glyphicon glyphicon glyphicon-book"></span> Getting Started
			</a>
		</div>
		<div class="btn-group navbar-btn">
			<a class="btn btn-default" type="button" href="/Search">
				<span class="glyphicon glyphicon glyphicon-search"></span>
			</a>
		</div>
        </div>
	</div>
	<div class="navbar-right-container navbar-right">
		<div class="btn-group navbar-btn user-info">
				
					
	<a class="user-name" id="login-button" href="#">
		Log in</a>
	<a class="user-name" id="signup-button" href="/SignUp">
		Sign up
	</a>

				
		</div>
		<span class="navbar-name-separator">&nbsp;&nbsp;&nbsp;&nbsp;</span>
		<div class="btn-group navbar-btn">
			
				<button class="btn btn-default dropdown-toggle" data-toggle="dropdown">
					<span class="glyphicon glyphicon-align-justify"></span>
				</button>
			<ul class="dropdown-menu academy-dropdown-menu">

					<li><a href="/about" id="about-btn" data-href="/Home/GetAboutCode">About</a></li>
					<li><a href="https://twitter.com/dotnetfiddle" id="twitter-btn" target="_blank">Twitter</a></li>
					<li><a href="https://dotnetcademy.net/" id="academy-btn" target="_blank">.NET Academy</a></li>
					<li><a href="https://chrome.google.com/webstore/detail/net-fiddle/ohjcieidjalbkdciooknjhkfemfajpjc" id="chrome-ext-btn" target="_blank">Chrome Ext</a></li>
					<li><a href="javascript:void(0);" id="support-btn" onclick=" showClassicWidget() ">Support</a></li>
					<li><a href="/Roadmap">Roadmap</a></li>
					<li><a href="/Terms">Terms</a></li>
					<li><a href="/PrivacyPolicy">Privacy Policy</a></li>
					<li><a href="/contact">Contact Us</a></li>

			</ul>
			
		</div>
	</div>
</div>
<div class="main docked">
	<div class="container">
    
		






<form action="/" id="CodeForm" method="post" onsubmit="return false;"><div id="share-dialog" class="sub-dialog">
	<span><b>Share Link</b></span><br />
	<input class="share-input share-link" id="ShareLink" name="ShareLink" onclick="this.select()" readonly="readonly" type="text" value="" />
	
	<span class="clipboard-status">Copied to clipboard</span>
	<a href="javascript:copyToClipboard('#ShareLink');" class="copy-clipboard" title="Copy to Clipboard"></a>
	<a href="javascript:void(0);" class="email-share" id="email-share" title="Send to Email"></a>
	<a href="#" class="twitter-share" title="Share to Twitter"></a>
	<a href="#" class="facebook-share" title="Share to Facebook"></a>
	<div id="email-form">
		<input class="share-input" data-val="true" data-val-email="*" data-val-required="*" id="email" name="email" placeholder="to email address" type="text" value="" />
		<input type="button" class="btn" style="font-size: 11px; padding: 4px 10px;" value="Send" id="email-send-btn" />
		<span id="email-status"></span>
	</div>
	<div style="position: relative;">
		<span><b>Embed on Your Page</b></span><br />
		<span class="clipboard-status-widget">Copied to clipboard</span>
		<input class="share-input share-widget-output" id="EmbedLink" name="EmbedLink" onclick="this.select()" readonly="readonly" type="text" value="" />
		
		<a href="javascript:copyToClipboard('#EmbedLink');" class="copy-clipboard" title="Copy to Clipboard"></a>
		<button id="widget-preview" type="button" class="btn" style="padding: 4px 10px; position: absolute; top: 20px; left: 268px;">Preview</button>

	</div>
	<div>
		<a href="#" class="advanced-widgetbuilder" id="widget-builder" style="color: #428bca;margin-top: 10px; font-size: 11px;">Advanced Widget Builder</a>
	</div>
	<div class="loading-layer">
		<img src="/content/images/ajax-loader.gif" />
	</div>
</div>
	 <!-- Console -->
    <input type="hidden" id="OriginalConsole" value="using System;
					
public class Program
{
	public static void Main()
	{
		Console.WriteLine(&quot;Hello World&quot;);
	}
}" />
	<!-- Script -->	
    <input type="hidden" id="OriginalScript" value="" />
    <!-- Mvc -->
    <input type="hidden" id="OriginalModel"/>
    <input type="hidden" id="OriginalView"/>
    <input type="hidden" id="OriginalController"/>
<input id="OriginalFiddleId" name="OriginalFiddleId" type="hidden" value="CsCons" /><input id="OriginalNuGetPackageVersionIds" name="OriginalNuGetPackageVersionIds" type="hidden" value="" /><input data-val="true" data-val-number="The field TimeOffset must be a number." data-val-required="The TimeOffset field is required." id="timezone" name="TimeOffset" type="hidden" value="0" />    <input id="NuGetPackageVersionIds" type="hidden" value="" />
	<div class="main docked">
		
		<div id="ukraine" class="container-banner container-banner-ukraine">
			<div class="text">We Stand with Ukraine</div>
		</div>
		<div class="expander"><span class="glyphicon glyphicon-chevron-right"></span></div>
		<div class="sidebar unselectable">
		</div>
		<div class="status-line">
			<input id="fiddle-name" name="Name" type="hidden" value="&lt;no name>" />
			<div class="name-container"></div>
			<div class="access-type-container">
				Access:
				<div class="btn-group">
					<button type="button" class="btn btn-default dropdown-toggle form-control" data-toggle="dropdown">
						<span>Only With Link</span>&nbsp;<span class="caret"></span>
					</button>
					<ul class="dropdown-menu" role="menu">
							<li><a href="#" data-value="Public">Public</a></li>
							<li><a href="#" data-value="OnlyWithLink">Only With Link</a></li>
					</ul>
				</div>
				<input data-val="true" data-val-required="The Access type field is required." id="access-type" name="AccessType" type="hidden" value="OnlyWithLink" />
			</div>
			
		</div>
		<div class="content">
		</div>
	</div>
    <div class="modal fade" id="preload-dialog" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h4 class="modal-title">Loading packages and dependencies</h4>
                </div>
                <div class="modal-body">
                </div>
            </div>
        </div>
    </div>
	<div class="modal fade" id="widget-builder-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
		<div class="modal-dialog" style="width: 960px;">
			<div class="modal-content">
				<div class="modal-header">
					<h4 class="modal-title" id="myModalLabel">Advanced Widget Builder</h4>
				</div>
				<div class="modal-body">
					<iframe style="border: 0px;" width="900px" height="545px" id="widget-builder-iframe"></iframe>
				</div>
				<div class="modal-footer">
				</div>
			</div>
		</div>
	</div>	
</form><div class="overlay" unselectable="on" onselectstart="return false;" onmousedown="return false;"></div>


<script id="sidebar-template" type="text/x-handlebars-template">
	<div class="sidebar-block">
		<button class="btn btn-default btn-xs btn-sidebar-toggle" type="button">
			<span class="glyphicon glyphicon-chevron-left"></span>
		</button>
		<button class="btn btn-default btn-xs btn-sidebar-pin" type="button">
			<span class="glyphicon glyphicon-pushpin"></span>
		</button>
		<div class="text-center"><strong>Options</strong></div>
	</div>
	<div class="sidebar-block">
		<span><strong><label for="Language">Language</label>:</strong></span>
		{{#ifCond compiler 'NetCore22'}}
		<br /><span id="StaticProjectType">{{language}}</span>
		{{else}}
		{{#select language}}
		<select class="sidebar-select form-control input-sm togetherjs" data-val="true" data-val-required="The Language field is required." id="Language" name="Language"><option selected="selected" value="CSharp">C#</option>
<option value="VbNet">VB.NET</option>
<option value="FSharp">F#</option>
</select>
		{{/select}}
		{{/ifCond}}
	</div>
	<div class="sidebar-block">
		<span><strong><label for="ProjectType">Project Type</label>:</strong></span>
		{{#ifExpr "language=='FSharp' || compiler=='NetCore22'"}}
		<br /><span id="StaticProjectType">{{projectType}}</span>
		{{else}}
		{{#select projectType}}
		<select class="sidebar-select form-control input-sm togetherjs" data-val="true" data-val-required="The Project Type field is required." id="ProjectType" name="ProjectType"><option selected="selected" value="Console">Console</option>
<option value="Script">Script</option>
<option value="Mvc">MVC</option>
<option value="Nancy">Nancy</option>
</select>
		{{/select}}
		{{/ifExpr}}
	</div>
	{{#ifExpr "language!='FSharp' && projectType!='Script' && projectType!='Nancy'"}}
	<div class="sidebar-block">
		<span><strong><label for="Compiler">Compiler</label>:</strong></span>
		{{#select compiler}}
		<select class="sidebar-select form-control input-sm togetherjs" data-val="true" data-val-required="The Compiler field is required." id="Compiler" name="Compiler"><option selected="selected" value="Net45">.NET 4.7.2</option>
<option value="Roslyn">Roslyn 4.8</option>
<option value="NetLatest">Latest (.NET 8)</option>
<option value="NetCore31">.NET Core 3.1</option>
<option value="Net5">.NET 5</option>
<option value="Net6">.NET 6</option>
<option value="Net7">.NET 7</option>
<option value="Net8">.NET 8</option>
</select>
		{{/select}}
	</div>
	{{/ifExpr}}
	{{#if layoutType}}
	<div class="sidebar-block">
		<span><strong><label for="LayoutType">Layout Type</label>:</strong></span>
		{{#select layoutType}}
		<select id="LayoutType" class="sidebar-select form-control input-sm togetherjs">
			<option value="sections">Sections</option>
			<option value="tabs">Tabs</option>
		</select>
		{{/select}}
	</div>
	{{/if}}
	{{#ifExpr "language=='FSharp' || (projectType!='Script' && compiler!='Roslyn')"}}
	<div class="sidebar-block">
		<div class="nuget-packages-wrap">
			<b>NuGet Packages: </b>
			<div class="nuget-panel hide-link" style="position: relative;">
				<ul class="nuget-packages"></ul>
				<input type="search" class="new-package form-control input-sm" placeholder="Package name..." />
				<a href="javascript:void(0);" class="add-package">Add Another</a>
				<div style="display:none;" class="nuget-search-spinner"></div>
			</div>
		</div>
	</div>
	{{/ifExpr}}
	<div class="sidebar-block autorun">
		<span><strong>Auto Run:</strong></span>
		<br>
		<label><input id="IsAutoRun_Yes" name="IsAutoRun" type="radio" {{#if isAutoRun}} checked="checked" {{/if}} value="True" />&nbsp;Yes</label>
		<label><input id="IsAutoRun_No" name="IsAutoRun" type="radio" {{#unless isAutoRun}} checked="checked" {{/unless}} value="False" />&nbsp;No</label>
	</div>

	<div class="sidebar-block ad">
		<script async type="text/javascript" src="//cdn.carbonads.com/carbon.js?serve=CK7DC27Y&placement=dotnetfiddlenet" id="_carbonads_js"/>
	</div>

		<div class="sidebar-menu">
			<ul>
				<li><a href="https://dotnetcademy.net/" target="_blank">.NET Academy</a></li>
				<li><a href="https://jobs.dotnetfiddle.net/" target="_blank" rel="nofollow">.NET Jobs</a></li>
				<li><a href="javascript:void(0);" id="support-btn" onclick=" showClassicWidget() ">Support</a></li>
				<li><a href="/Roadmap">Roadmap</a></li>
				<li><a href="/Terms">Terms</a></li>
				<li><a href="/contact">Contact us</a></li>
			</ul>
		</div>
</script>

<script id="main-console-template" type="text/x-handlebars-template">
    <div class="layout-container">
        <div class="pane">
            <textarea id="Console" class="code-block">{{codeBlocks.Console}}</textarea>
        </div>
        <div class="output-container">
            <div class="output-pane pane">
                <div id="output" class="output"></div>
                <div id="input" contenteditable="true"></div>
            </div>
            <div class="stats-pane pane">
                <div id="stats" style="height: 100%; display: none; font-size: 13px;"></div>
                <div id="stats-loader" style="display: none;">
                    <div class="bg"></div>
                    <div class="spin"></div>
                </div>
            </div>
        </div>
    </div>
</script>

<script id="main-script-template" type="text/x-handlebars-template">
    <div class="layout-container">
        <div class="pane">
            <textarea id="Script" class="code-block">{{codeBlocks.Script}}</textarea>
        </div>
        <div class="output-container">
            <div class="output-pane pane">
                <div id="output" class="output"></div>
                <div id="input" contenteditable="true"></div>
            </div>
            <div class="stats-pane pane">
                <div id="stats" style="height: 100%; display: none; font-size: 13px;"></div>
                <div id="stats-loader" style="display: none;">
                    <div class="bg"></div>
                    <div class="spin"></div>
                </div>
            </div>
        </div>
    </div>
</script>

<script id="main-mvc-sections-template" type="text/x-handlebars-template">
    <div class="layout-container">
        <div class="code-container">
            <div class="top-code-container">
                <div class="model-container section pane">
                    <textarea id="Model" class="code-block">{{codeBlocks.Model}}</textarea>
                    <span class="section-label" style="opacity: 0.8;">Model</span>
                </div>
                <div class="view-container section pane">
                    <textarea id="View" class="code-block" mode="razor">{{codeBlocks.View}}</textarea>
                    <span class="section-label" style="opacity: 0.8;">View</span>
                </div>
            </div>
            <div class="bottom-code-container">
                <div class="controller-container section pane">
                    <textarea id="Controller" class="code-block">{{codeBlocks.Controller}}</textarea>
                    <span class="section-label" style="opacity: 0.8;">Controller</span>
                </div>
                <div class="page-container section pane" style="overflow: hidden;">
                    <iframe id="mvc-output-iframe" src="" width="100%" height="100%" frameborder="0"></iframe>
                    <a href="javascript: void(0);" class="section-label show" style="opacity: 0.8;" id="view-fullscreen" title="View in Full Screen" target="_blank">View in Full Screen</a>
                </div>
            </div>
        </div>
        <div class="output-container">
            <div class="output-pane pane">
                <div id="output" class="output"></div>
                <div id="input" contenteditable="true"></div>
            </div>
            <div class="stats-pane pane">
                <div id="stats" style="height: 100%; display: none; font-size: 13px;"></div>
                <div id="stats-loader" style="display: none;">
                    <div class="bg"></div>
                    <div class="spin"></div>
                </div>
            </div>
        </div>

    </div>
</script>

<script id="main-mvc-tabs-template" type="text/x-handlebars-template">
    <div class="layout-container">
        <div class="code-container">
            <div class="tabs-code-container pane" style="overflow: hidden; background-color: #fafafa;border: none;">
                <ul class="nav nav-tabs dnf-tabs">
                    <li class="active"><a href="#tabs-1" data-toggle="tab">Model</a></li>
                    <li><a href="#tabs-2" data-toggle="tab">View</a></li>
                    <li><a href="#tabs-3" data-toggle="tab">Controller</a></li>
                </ul>

                <div class="tab-content" style="height: 100%;padding-bottom: 35px;padding-top:0px;">
                    <div class="tab-pane active" id="tabs-1">
                        <textarea id="Model" class="code-block">{{codeBlocks.Model}}</textarea>
                    </div>
                    <div class="tab-pane" id="tabs-2">
                        <textarea id="View" class="code-block" mode="razor">{{codeBlocks.View}}</textarea>
                    </div>
                    <div class="tab-pane" id="tabs-3">
                        <textarea id="Controller" class="code-block">{{codeBlocks.Controller}}</textarea>
                    </div>
                </div>
            </div>
            <div class="page-container pane">
                <iframe id="mvc-output-iframe" src="" width="100%" height="500px" frameborder="0"></iframe>
                <a href="javascript: void(0);" class="section-label show" style="opacity: 0.8;" id="view-fullscreen" title="View in Full Screen" target="_blank">View in Full Screen</a>
            </div>
        </div>
        <div class="output-container">
            <div class="output-pane pane">
                <div id="output" class="output"></div>
                <div id="input" contenteditable="true"></div>
            </div>
            <div class="stats-pane pane">
                <div id="stats" style="height: 100%; display: none; font-size: 13px;"></div>
                <div id="stats-loader" style="display: none;">
                    <div class="bg"></div>
                    <div class="spin"></div>
                </div>
            </div>
        </div>

    </div>
</script>

<script id="main-nancy-sections-template" type="text/x-handlebars-template">
   <div class="layout-container">
        <div class="code-container">
            <div class="top-code-container">
                <div class="model-container section pane">
                    <textarea id="Model" class="code-block">{{codeBlocks.Model}}</textarea>
                    <span class="section-label" style="opacity: 0.8;">Model</span>
                </div>
                <div class="view-container section pane">
                    <textarea id="View" class="code-block" mode="razor">{{codeBlocks.View}}</textarea>
                    <span class="section-label" style="opacity: 0.8;">View</span>
                </div>
            </div>
            <div class="bottom-code-container">
                <div class="controller-container section pane">
                    <textarea id="Controller" class="code-block">{{codeBlocks.Controller}}</textarea>
                    <span class="section-label" style="opacity: 0.8;">Module</span>
                </div>
                <div class="page-container section pane" style="overflow: hidden;">
                    <iframe id="mvc-output-iframe" src="" width="100%" height="100%" frameborder="0"></iframe>
                    <a href="javascript: void(0);" class="section-label show" style="opacity: 0.8;" id="view-fullscreen" title="View in Full Screen" target="_blank">View in Full Screen</a>
                </div>
            </div>
        </div>
        <div class="output-container">
            <div class="output-pane pane">
                <div id="output" class="output"></div>
                <div id="input" contenteditable="true"></div>
            </div>
            <div class="stats-pane pane">
                <div id="stats" style="height: 100%; display: none; font-size: 13px;"></div>
                <div id="stats-loader" style="display: none;">
                    <div class="bg"></div>
                    <div class="spin"></div>
                </div>
            </div>
        </div>

    </div>
</script>

<script id="main-nancy-tabs-template" type="text/x-handlebars-template">
    <div class="layout-container">
        <div class="code-container">
            <div class="tabs-code-container pane" style="overflow: hidden; background-color: #fafafa;border: none;">
                <ul class="nav nav-tabs dnf-tabs">
                    <li class="active"><a href="#tabs-1" data-toggle="tab">Model</a></li>
                    <li><a href="#tabs-2" data-toggle="tab">View</a></li>
                    <li><a href="#tabs-3" data-toggle="tab">Module</a></li>
                </ul>

                <div class="tab-content" style="height: 100%;padding-bottom: 35px;padding-top:0px;">
                    <div class="tab-pane active" id="tabs-1">
                        <textarea id="Model" class="code-block">{{codeBlocks.Model}}</textarea>
                    </div>
                    <div class="tab-pane" id="tabs-2">
                        <textarea id="View" class="code-block" mode="razor">{{codeBlocks.View}}</textarea>
                    </div>
                    <div class="tab-pane" id="tabs-3">
                        <textarea id="Controller" class="code-block">{{codeBlocks.Controller}}</textarea>
                    </div>
                </div>
            </div>
            <div class="page-container pane">
                <iframe id="mvc-output-iframe" src="" width="100%" height="500px" frameborder="0"></iframe>
                <a href="javascript: void(0);" class="section-label show" style="opacity: 0.8;" id="view-fullscreen" title="View in Full Screen" target="_blank">View in Full Screen</a>
            </div>
        </div>
        <div class="output-container">
            <div class="output-pane pane">
                <div id="output" class="output"></div>
                <div id="input" contenteditable="true"></div>
            </div>
            <div class="stats-pane pane">
                <div id="stats" style="height: 100%; display: none; font-size: 13px;"></div>
                <div id="stats-loader" style="display: none;">
                    <div class="bg"></div>
                    <div class="spin"></div>
                </div>
            </div>
        </div>
		
    </div>
</script>

<div id="sponsor-0" class="container-sponsor container-sponsor-zzzprojects" style="display: none;">
	<a href="https://entityframework-extensions.net/" onclick="ga('send', 'event', { eventAction: 'sponsor-ef-extensions' });" target="_blank">
		<img src="/Content/images/sponsor/zzzprojects-logo-50x36.png"/>
		<div class="text">
			Entity Framework Extensions - Fastest Way of Inserting Entities
			<span>Trusted by over 5000 business to improve their application performance</span>
    </div>
		<span class="link">Try It</span>
	</a>
</div>

<div id="sponsor-1" class="container-sponsor container-sponsor-zzzprojects" style="display: none;">
	<a href="https://entityframework-extensions.net/" onclick="ga('send', 'event', { eventAction: 'sponsor-ef-extensions' });" target="_blank">
		<img src="/Content/images/sponsor/zzzprojects-logo-50x36.png"/>
		<div class="text">
			Entity Framework Extensions - Bulk Extensions to Improve Performance
			<span>BulkInsert | BulkUpdate | BulkMerge | BulkSaveChanges | WhereBulkContains</span>
		</div>
		<span class="link">Learn More</span>
	</a>
</div>

<div id="sponsor-2" class="container-sponsor container-sponsor-zzzprojects" style="display: none;">
	<a href="https://entityframework-extensions.net/" onclick="ga('send', 'event', { eventAction: 'sponsor-ef-extensions' });" target="_blank">
		<img src="/Content/images/sponsor/zzzprojects-logo-50x36.png"/>
		<div class="text">
			Entity Framework Extensions - Bulk Insert Entities with EF Core
			<span>Over 20 million downloads | Support all EF6 and EF Core versions</span>
		</div>
		<span class="link">Learn More</span>
	</a>
</div>

<div id="sponsor-3" class="container-sponsor container-sponsor-zzzprojects" style="display: none;">
	<a href="https://dapper-plus.net/" onclick="ga('send', 'event', { eventAction: 'sponsor-dapper-plus' });" target="_blank">
		<img src="/Content/images/sponsor/zzzprojects-logo-50x36.png"/>
		<div class="text">
			Dapper Plus - A Must Have Extensions to Boost your Performance
			<span>Extend your IDbConnection with High-Performance Bulk Operations</span>
		</div>
		<span class="link">Learn More</span>
	</a>
</div>

<div id="sponsor-4" class="container-sponsor container-sponsor-zzzprojects" style="display: none;">
	<a href="https://eval-expression.net/" onclick="ga('send', 'event', { eventAction: 'sponsor-eval' });" target="_blank">
		<img src="/Content/images/sponsor/zzzprojects-logo-50x36.png"/>
		<div class="text">
			C# Eval Expression - Evaluate, Compile and Execute C# Code at Runtime
			<span>LINQ Dynamic | Eval.Execute(code) | Eval.Compile(code)</span>
		</div>
		<span class="link">Learn More</span>
	</a>
</div>

<div id="sponsor-5" class="container-sponsor container-sponsor-pandaflow" style="display: none;">
	<a href="https://entechsolutions.com/?utm_source=dnf-site&utm_medium=banner&utm_campaign=dnf-logo1" onclick="ga('send', 'event', { eventAction: 'sponsor-entechsolutions' });" target="_blank">
		<img src="/Content/images/sponsor/hire-1.png" style="height: 70px" />
	</a>
</div>

<div id="sponsor-6" class="container-sponsor container-sponsor-pandaflow" style="display: none;">
	<a href="https://entechsolutions.com/?utm_source=dnf-site&utm_medium=banner&utm_campaign=dnf-logo2" onclick="ga('send', 'event', { eventAction: 'sponsor-entechsolutions' });" target="_blank">
		<img src="/Content/images/sponsor/hire-2.png" style="height: 70px" />
	</a>
</div>

<div id="sponsor-7" class="container-sponsor container-sponsor-pandaflow" style="display: none;">
	<a href="https://entechsolutions.com/?utm_source=dnf-site&utm_medium=banner&utm_campaign=dnf-logo3" onclick="ga('send', 'event', { eventAction: 'sponsor-entechsolutions' });" target="_blank">
		<img src="/Content/images/sponsor/hire-3.png" style="height: 70px" />
	</a>
</div>

<div id="sponsor-8" class="container-sponsor container-sponsor-pandaflow" style="display: none;">
	<a href="https://entechsolutions.com/?utm_source=dnf-site&utm_medium=banner&utm_campaign=dnf-logo4" onclick="ga('send', 'event', { eventAction: 'sponsor-entechsolutions' });" target="_blank">
		<img src="/Content/images/sponsor/hire-4.png" style="height: 70px" />
	</a>
</div>

	</div>
</div>



	</div>

	<script>
		if (!window.location.origin) {
			window.location.origin = window.location.protocol + "//" + window.location.hostname + (window.location.port ? ':' + window.location.port : '');
		}
		function copyToClipboard(element) {
			var $temp = $("<input>");
			$("body").append($temp);
			$temp.val($(element).val()).select();
			document.execCommand("copy");
			$temp.remove();
		}
	</script>
	<script src="/bundles/jquery?v=UgyEMAYOuSB9Bb6HcOEVHpd6fIIp54yF086SRNVcdIY1"></script>

	<script src="/bundles/jqueryval?v=uGU96Je1z8LG2_PzLPMjBJ2v03RgJhQZjQZLGOWBzpM1"></script>


	
    <script src="/bundles/utils?v=DG6S1LVYLBzhp-8AWPGB2sCat3YRoqackHFy60l9tu01"></script>

	
			
		<div class="modal-content" id="viewil-dialog" style="display: none; width:1000px;">
			<div class="modal-header">
				<button type="button" class="close" id="viewil-dialog-hide">&times;</button>
				<h4 class="modal-title" id="viewillabel">View IL Code</h4>
			</div>
			<div class="modal-body">
			</div>
		</div>
	<script src="/bundles/jqueryui?v=lc_RCpFs7BhXflBrmcGNMTXHnVlW_8_i6uPgTjDnxFk1"></script>

	<script src="/bundles/codemirror?v=8iuG4ZglK5P7ddRQwqFQU-61aYPjjKDbq7ityHU0NDs1"></script>

    <script src="/bundles/jqueryval?v=uGU96Je1z8LG2_PzLPMjBJ2v03RgJhQZjQZLGOWBzpM1"></script>

    <script src="/bundles/common?v=PK05ca13iPAll19qXferuNH3aSmUCsczCiCpObzxY5w1"></script>

	<script src="/bundles/desktop?v=r6_KhoblbqZNELghepPQsjgbEy47Hejmk0w6LYrckaU1"></script>


	<script type="text/javascript">

		window.TogetherJSConfig = {
			hubBase: "https://togetherjs.dotnetfiddle.net"
		};
		env.siteMode = siteModes.full;
		env.auth = false;
	</script>
    <script src="https://togetherjs.com/togetherjs-min.js"></script>

	
    
	<script type="text/javascript">


		var initVersions = [
		];

		function tryGetFromStorage(fiddleId, blockName) {
			
			if (fiddleId && fiddleId.length && $.cookie && ($.cookie("OriginalFiddleId")==null || $.cookie("OriginalFiddleId")==fiddleId) && $.cookie("UseLocalStorage") == "true" && window.location.pathname == "/" && (!window.location.search || !window.location.search.length)) {
				var code = localStorage.getItem(blockName);
				if (code != null && code != "" && code != "null") {
					localStorage.removeItem(blockName);
					$.removeCookie(blockName);
					return code;
				}
			}
			return $('#Original' + blockName).val();
		}
		
		function tryGetCompilerFromCookies(fiddleId, compiler) {
			if(!fiddleId || !fiddleId.length)//fiddle constructed by url params, so do not use cookies
				return compiler;
			
			if ($.cookie && $.cookie("Compiler") && $.cookie("UseLocalStorage") == "true" && window.location.pathname == "/" && (!window.location.search || !window.location.search.length)) {
				var comp = $.cookie("Compiler");
				$.removeCookie("Compiler");
				return comp;
			}

			return compiler;
		}

		$(document).ready(function() {
			nugetPackageManager.init(initVersions);


				
			var comp = tryGetCompilerFromCookies('CsCons', 'Net45');
			fiddle.init({
                fiddleId: 'CsCons',
            	language: 'CSharp',
				compiler: comp,
				ownerId:null,
            	ownerName: '.NET Fiddle',
                projectType: 'Console',
                layoutType: '',
				codeBlocks: { 'Console': tryGetFromStorage('CsCons', 'Console') },

                isAutoRun: 'False'.toLowerCase() == 'true'
            });
			

			fiddle.isInUserFiddles(false);

			fiddle.render();

				$("#fiddle-name").val("");

			
			fiddle.initMeta(false, true);
			
		});

		$(function() {

			// Label events for Mvc sections layout
			$('body').on('mouseenter', '.section', function() {
				var obj = $(this).find('.section-label');

				if ($(obj).hasClass('show'))
					$(obj).css('opacity', 1);
				else
					$(obj).stop(true, true).fadeOut(500);
			});
			$('body').on('mouseleave', '.section', function() {
				var obj = $(this).find('.section-label');

				if ($(obj).hasClass('show'))
					$(obj).css('opacity', 0.8);
				else
					$(obj).stop(true, true).fadeIn(500);
			});

			// For Mvc tabs layout
			$('body').on('shown.bs.tab', 'a[data-toggle="tab"]', function(e) {
				var href = $(e.target).attr('href');
				var id = $('.tab-content ' + href + ' textarea').attr('id');

				var editors = fiddle.getEditors();
				editors[id].refresh();
			});

			// Widget Builder
			$('#widget-builder').click(function(e) {
				e.preventDefault();
				var self = this;
				var url = self.href;

				$("#widget-builder-iframe").animate({ opacity: 0 }, { duration: 10, queue: true });

				if ($("#widget-builder-iframe").attr("src") != url) {
					$("#widget-builder-iframe").attr("src", url);
				}

				$("#widget-builder-modal").modal("show");

				$("#widget-builder-iframe").delay(600).animate({ opacity: 1 }, { duration: 200, queue: true });

			});

			function closeSidebar() {
				$('.sidebar').animate({
					left: '-180px'
				}, 200);
			}

			function openSidebar() {
				$('.sidebar').animate({
					left: '0px'
				}, 200);
			}

			$('body').on('click', '.expander', function(ev) {
				ev.stopPropagation();

				openSidebar();
			});

			$('body').on('click', '.sidebar', function(ev) {
				ev.stopPropagation();
			});

			$('body').click(function() {

				if (!$('.main').hasClass('docked')) closeSidebar();
			});

			$('body').on('click', '.sidebar .btn-sidebar-toggle', function() {
				var self = this;
				var isResize = $('.main').hasClass('docked');

				$('.main').removeClass('docked');

				closeSidebar();

				if (isResize)
					$(window).trigger('resize');
			});

			$('body').on('click', '.sidebar .btn-sidebar-pin', function() {
				var self = this;

				if ($('.main').hasClass('docked')) $('.main').removeClass('docked');
				else $('.main').addClass('docked');

				$(window).trigger('resize');
			});


		});
		

		$.validator.setDefaults({
			highlight: function (element) {
				$(element).closest(".form-group").addClass("has-error");
				//$(element).closest(".form-group").removeClass("has-success");
			},
			unhighlight: function (element) {
				$(element).closest(".form-group").removeClass("has-error");
				//$(element).closest(".form-group").addClass("has-success");
			},
			errorClass: 'help-block',
			showErrors: function (errorMap, errorList) {
				var i, elements;

				for (i = 0, elements = this.validElements() ; elements[i]; i++) {
					var $element = $(elements[i]);
					var $group = $element.closest(".form-group");
					$group.find(".field-validation-error").each(function () {
						$(this).remove();
					});
					this.settings.unhighlight.call(this, elements[i], this.settings.errorClass, this.settings.validClass);
				}

				$.each(errorList, function (ix, v) {
					var $element = $(v.element);
					var $group = $element.closest(".form-group");
					$group.find(".field-validation-error").each(function () {
						$(this).remove();
					});

					$group.append($("<span>").addClass("field-validation-error help-block").append(v.message));
					$.validator.defaults.highlight(v.element);
				});

				this.toHide = this.toHide.not(this.toShow);
				this.hideErrors();
				this.addWrapper(this.toShow).show();
			}
		});
		
		var setPopupStatus = function (status) {
			if (status) {
				//continue
				$.ajax({
					url: "/LogIn/RemoteLogin",
					type: "POST",
					data: JSON.stringify({ loginTypeId: loginType }),
					dataType: 'json',
					contentType: "application/json; charset=utf-8",
					success: function (resp) {
						if (resp.IsSuccess) {
							//
						}
					}
				});
			}
		};

		var loginType;
	</script>

	<script src="/Content/packages/bootstrap-3.0.2/js/bootstrap.js"></script>



		<script>
			(function (i, s, o, g, r, a, m) {
				i['GoogleAnalyticsObject'] = r;
				i[r] = i[r] || function () {
					(i[r].q = i[r].q || []).push(arguments)
				}, i[r].l = 1 * new Date();
				a = s.createElement(o),
				m = s.getElementsByTagName(o)[0];
				a.async = 1;
				a.src = g;
				m.parentNode.insertBefore(a, m)
			})(window, document, 'script', '//www.google-analytics.com/analytics.js', 'ga');

			ga('create', 'UA-45542977-1', 'dotnetfiddle.net');
			ga('send', 'pageview');
		</script>

	
	<style id="profiler-minimizer-css">
		.profiler-results {
			display: none;
		}
	</style>
	<script type="text/javascript" id="profiler-minimizer">
		$(document).ready(function () {
			 var e = function () {
			 	var e = $(".profiler-results");
			 	if (e.length == 0) return false;
			 	e.addClass("profiler-min");
				 return true;
			 };
			
			var t = function () {
				var n = e();
				if (n) {
					$("#profiler-minimizer").remove(); $("#profiler-minimizer-css").remove();
					return;
				}
				setTimeout(t, 50);
			};
			t();
		})
	</script>
	
	<script>
		// script to dramatically reduce bounce rate
		setTimeout(gaIsActive, 20000);
		setTimeout(gaIsActive, 60000);
		setTimeout(gaIsActive, 90000);
		setTimeout(gaIsActive, 120000);
		setTimeout(gaIsActive, 150000);

		function gaIsActive() {
			if (!document.hidden) ga('send', 'event', { eventAction: 'TimeOnPage' });
		}
	</script>

</body>
</html>
