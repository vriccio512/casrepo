<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1" />
<meta name="generator" content="pdoc 0.9.2" />
<title>vra_module API documentation</title>
<meta name="description" content="vRealize Automation 8.x Module for Salt
…" />
<link rel="preload stylesheet" as="style" href="https://cdnjs.cloudflare.com/ajax/libs/10up-sanitize.css/11.0.1/sanitize.min.css" integrity="sha256-PK9q560IAAa6WVRRh76LtCaI8pjTJ2z11v0miyNNjrs=" crossorigin>
<link rel="preload stylesheet" as="style" href="https://cdnjs.cloudflare.com/ajax/libs/10up-sanitize.css/11.0.1/typography.min.css" integrity="sha256-7l/o7C8jubJiy74VsKTidCy1yBkRtiUGbVkYBylBqUg=" crossorigin>
<link rel="stylesheet preload" as="style" href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/10.1.1/styles/github.min.css" crossorigin>
<style>:root{--highlight-color:#fe9}.flex{display:flex !important}body{line-height:1.5em}#content{padding:20px}#sidebar{padding:30px;overflow:hidden}#sidebar > *:last-child{margin-bottom:2cm}.http-server-breadcrumbs{font-size:130%;margin:0 0 15px 0}#footer{font-size:.75em;padding:5px 30px;border-top:1px solid #ddd;text-align:right}#footer p{margin:0 0 0 1em;display:inline-block}#footer p:last-child{margin-right:30px}h1,h2,h3,h4,h5{font-weight:300}h1{font-size:2.5em;line-height:1.1em}h2{font-size:1.75em;margin:1em 0 .50em 0}h3{font-size:1.4em;margin:25px 0 10px 0}h4{margin:0;font-size:105%}h1:target,h2:target,h3:target,h4:target,h5:target,h6:target{background:var(--highlight-color);padding:.2em 0}a{color:#058;text-decoration:none;transition:color .3s ease-in-out}a:hover{color:#e82}.title code{font-weight:bold}h2[id^="header-"]{margin-top:2em}.ident{color:#900}pre code{background:#f8f8f8;font-size:.8em;line-height:1.4em}code{background:#f2f2f1;padding:1px 4px;overflow-wrap:break-word}h1 code{background:transparent}pre{background:#f8f8f8;border:0;border-top:1px solid #ccc;border-bottom:1px solid #ccc;margin:1em 0;padding:1ex}#http-server-module-list{display:flex;flex-flow:column}#http-server-module-list div{display:flex}#http-server-module-list dt{min-width:10%}#http-server-module-list p{margin-top:0}.toc ul,#index{list-style-type:none;margin:0;padding:0}#index code{background:transparent}#index h3{border-bottom:1px solid #ddd}#index ul{padding:0}#index h4{margin-top:.6em;font-weight:bold}@media (min-width:200ex){#index .two-column{column-count:2}}@media (min-width:300ex){#index .two-column{column-count:3}}dl{margin-bottom:2em}dl dl:last-child{margin-bottom:4em}dd{margin:0 0 1em 3em}#header-classes + dl > dd{margin-bottom:3em}dd dd{margin-left:2em}dd p{margin:10px 0}.name{background:#eee;font-weight:bold;font-size:.85em;padding:5px 10px;display:inline-block;min-width:40%}.name:hover{background:#e0e0e0}dt:target .name{background:var(--highlight-color)}.name > span:first-child{white-space:nowrap}.name.class > span:nth-child(2){margin-left:.4em}.inherited{color:#999;border-left:5px solid #eee;padding-left:1em}.inheritance em{font-style:normal;font-weight:bold}.desc h2{font-weight:400;font-size:1.25em}.desc h3{font-size:1em}.desc dt code{background:inherit}.source summary,.git-link-div{color:#666;text-align:right;font-weight:400;font-size:.8em;text-transform:uppercase}.source summary > *{white-space:nowrap;cursor:pointer}.git-link{color:inherit;margin-left:1em}.source pre{max-height:500px;overflow:auto;margin:0}.source pre code{font-size:12px;overflow:visible}.hlist{list-style:none}.hlist li{display:inline}.hlist li:after{content:',\2002'}.hlist li:last-child:after{content:none}.hlist .hlist{display:inline;padding-left:1em}img{max-width:100%}td{padding:0 .5em}.admonition{padding:.1em .5em;margin-bottom:1em}.admonition-title{font-weight:bold}.admonition.note,.admonition.info,.admonition.important{background:#aef}.admonition.todo,.admonition.versionadded,.admonition.tip,.admonition.hint{background:#dfd}.admonition.warning,.admonition.versionchanged,.admonition.deprecated{background:#fd4}.admonition.error,.admonition.danger,.admonition.caution{background:lightpink}</style>
<style media="screen and (min-width: 700px)">@media screen and (min-width:700px){#sidebar{width:30%;height:100vh;overflow:auto;position:sticky;top:0}#content{width:70%;max-width:100ch;padding:3em 4em;border-left:1px solid #ddd}pre code{font-size:1em}.item .name{font-size:1em}main{display:flex;flex-direction:row-reverse;justify-content:flex-end}.toc ul ul,#index ul{padding-left:1.5em}.toc > ul > li{margin-top:.5em}}</style>
<style media="print">@media print{#sidebar h1{page-break-before:always}.source{display:none}}@media print{*{background:transparent !important;color:#000 !important;box-shadow:none !important;text-shadow:none !important}a[href]:after{content:" (" attr(href) ")";font-size:90%}a[href][title]:after{content:none}abbr[title]:after{content:" (" attr(title) ")"}.ir a:after,a[href^="javascript:"]:after,a[href^="#"]:after{content:""}pre,blockquote{border:1px solid #999;page-break-inside:avoid}thead{display:table-header-group}tr,img{page-break-inside:avoid}img{max-width:100% !important}@page{margin:0.5cm}p,h2,h3{orphans:3;widows:3}h1,h2,h3,h4,h5,h6{page-break-after:avoid}}</style>
<script defer src="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/10.1.1/highlight.min.js" integrity="sha256-Uv3H6lx7dJmRfRvH8TH6kJD1TSK1aFcwgx+mdg3epi8=" crossorigin></script>
<script>window.addEventListener('DOMContentLoaded', () => hljs.initHighlighting())</script>
</head>
<body>
<main>
<article id="content">
<header>
<h1 class="title">Module <code>vra_module</code></h1>
</header>
<section id="section-intro">
<h1 id="vrealize-automation-8x-module-for-salt">vRealize Automation 8.x Module for Salt</h1>
<p>Provides methods to configure and setup vRealize Automation</p>
<p>Requirements:
SaltStack Config
vRealize Automation 8.x</p>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">&#34;&#34;&#34;
vRealize Automation 8.x Module for Salt
========================================

Provides methods to configure and setup vRealize Automation

Requirements:
SaltStack Config
vRealize Automation 8.x

&#34;&#34;&#34;


#Import python libs
import logging
try:
    import json
    import requests
    import urllib3
    HAS_DEPENDENCIES = True
except ImportError:
    HAS_DEPENDENCIES = False

log = logging.getLogger(__name__)

__virtual_name__ = &#39;vra&#39;

def __virtual__():
    &#39;&#39;&#39;
    Only load vra if requests is available
    &#39;&#39;&#39;
    if HAS_DEPENDENCIES:
        return __virtual_name__
    else:
        return False, &#39;The vra module cannot be loaded: dependency packages unavailable.&#39;

urllib3.disable_warnings()

def set_bas_url(url):
    api_url_base = &#34;https://&#34; + url + &#34;/&#34;
    return api_url_base

def extract_values(obj, key):
    &#34;&#34;&#34;
    Pull all values of specified key from nested JSON.
    &#34;&#34;&#34;
    arr = []
    def extract(obj, arr, key):
        &#34;&#34;&#34;Recursively search for values of key in JSON tree.&#34;&#34;&#34;
        if isinstance(obj, dict):
            for k, v in obj.items():
                if isinstance(v, (dict, list)):
                    extract(v, arr, key)
                elif k == key:
                    arr.append(v)
        elif isinstance(obj, list):
            for item in obj:
                extract(item, arr, key)
        return arr
    results = extract(obj, arr, key)
    return results

def get_token(url,username, password):
    &#34;&#34;&#34;
    Retrieve Session Token from vRealize Automation
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;}
    api_url = &#39;{0}csp/gateway/am/api/login?access_token&#39;.format(api_url_base)
    data =  {
              &#34;username&#34;: username,
              &#34;password&#34;: password
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        key = json_data[&#39;access_token&#39;]
        return key
    else:
        return response.status_code

##########Cloud Assembly Configuration Functions##########

######Cloud Account and Cloud Zones######
def create_aws_ca(url,username,password,aws_key_id,aws_access_key,name):
    &#34;&#34;&#34;
    Setup and configure AWS Cloud Accounts

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    aws_key_id = AWS Key

    aws_access_key = AWS Access Key

    name = name of AWS Integration

    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/cloud-accounts-aws&#39;.format(api_url_base)
    data =  {
                &#34;description&#34;: &#34;AWS Cloud Account&#34;,
                &#34;accessKeyId&#34;: aws_key_id,
                &#34;secretAccessKey&#34;: aws_access_key,
                &#34;cloudAccountProperties&#34;: {

                },
                &#34;regionIds&#34;: [
                    &#34;us-west-1&#34;
                ],
                &#34;createDefaultZones&#34; : &#34;true&#34;,
                &#34;name&#34;: name
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        print(&#39;Successfully Created AWS Cloud Account&#39;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def create_azure_ca(url,username,password,sub_id,ten_id,app_id,app_key,name,region_id):
    &#34;&#34;&#34;
    Setup and Create Azure Cloud Account

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    sub_id = Azure Subscription ID

    ten_id = Azure Tenant ID

    app_id = Azure Client Application ID

    app_key = Azure Client Application Secret Key

    region_id = Azure Region (example: eastus)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/cloud-accounts-azure&#39;.format(api_url_base)
    data =  {
              &#34;name&#34;: name,
              &#34;description&#34;: &#34;Azure Cloud Account&#34;,
              &#34;subscriptionId&#34;: sub_id,
              &#34;tenantId&#34;: ten_id,
              &#34;clientApplicationId&#34;: app_id,
              &#34;clientApplicationSecretKey&#34;: app_key,
              &#34;regionIds&#34;: [
                  region_id
               ],
              &#34;createDefaultZones&#34;: &#34;true&#34;
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        print(&#39;Successfully Created Azure Cloud Account&#39;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def create_vsphere_ca(url,username,password,vc_hostname,vc_username,vc_password,name,region_id):
    &#34;&#34;&#34;
    Setup and Create vSphere Cloud Account

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    vc_hostname = vCenter IP / FQDN

    vc_username: vCenter Administrator User

    vc_password = vCenter Password

    name = Cloud Account Name

    region_id = vCenter Datacenter (i.e. Datacenter:datacenter-2)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/cloud-accounts-vsphere&#39;.format(api_url_base)
    data = {
              &#34;name&#34;: name,
              &#34;hostName&#34;: vc_hostname,
              &#34;acceptSelfSignedCertificate&#34;: &#34;true&#34;,
              &#34;dcid&#34;: &#34;onprem&#34;,
              &#34;username&#34;: vc_username,
              &#34;password&#34;: vc_password,
              &#34;regionIds&#34;: [
                region_id
              ],
              &#34;createDefaultZones&#34;: &#34;true&#34;
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        print(&#39;Successfully Created vCenter Cloud Account&#39;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def get_ca_by_name(url,username,password,vc_ca_name):
    &#34;&#34;&#34;
    Retrieve Cloud Account by its names for further configurations

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    vc_ca_name = Cloud Account Name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/cloud-accounts&#39;.format(api_url_base,vc_ca_name)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            ca_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if ca_name == vc_ca_name:
                print(&#34;Found Cloud Account: &#34; + vc_ca_name)
                ca_json = json_data[&#39;content&#39;][n]
                return ca_json
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For Cloud Zone: &#34; + vc_ca_name)
                return &#34;No Match Found For Cloud Zone: &#34; + vc_ca_name
                break
    else:
        print(response.status_code)
        return response.status_code

def create_nsxt_ca(url,username,password,nsx_hostname,nsx_username,nsx_password,name,vc_ca_name):
    &#34;&#34;&#34;
    Create NSX Cloud Account

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    nsx_hostname = FQDN of NSX Manager Instance

    nsx_username = NSX Admin User

    nsx_password = NSX Admin Password

    name = Provide a name for the Cloud Account

    vc_ca_name = Name of Cloud Account to associate with NSX Cloud Account
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    ca_json = get_ca_by_name(url,username,password,vc_ca_name)
    ca_id = ca_json[&#39;id&#39;]
    ca_array = []
    ca_array.append(ca_id)
    api_url = &#39;{0}iaas/api/cloud-accounts-nsx-t&#39;.format(api_url_base)
    data = {
              &#34;hostName&#34;: nsx_hostname,
              &#34;acceptSelfSignedCertificate&#34;: &#34;true&#34;,
              &#34;password&#34;: nsx_password,
              &#34;dcid&#34;: &#34;onprem&#34;,
              &#34;associatedCloudAccountIds&#34;: ca_array,
              &#34;managerMode&#34;: &#34;true&#34;,
              &#34;name&#34;: name,
              &#34;description&#34;: &#34;NSX-T Cloud Account&#34;,
              &#34;username&#34;: nsx_username
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        print(&#39;Successfully Created NSX-T Cloud Account&#39;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def get_czid_by_name(url,username,password,czname):
    &#34;&#34;&#34;
    Retrieve Cloud Zone by Name for further configurations

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    czname = Cloud Zone Name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/zones&#39;.format(api_url_base,czname)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            cz_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if cz_name == czname:
                print(&#34;Found Cloud Zone: &#34; + czname)
                cz_id = json_data[&#39;content&#39;][n][&#39;id&#39;]
                return cz_id
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For Cloud Zone: &#34; + czname)
                return &#34;No Match Found For Cloud Zone: &#34; + czname
                break
    else:
        print(response.status_code)
        return response.status_code

def tag_cloudzone(url,username,password,czname,tag_key,tag_value):
    &#34;&#34;&#34;
    Tag Cloud Zone

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    czname = Cloud Zone Name

    tag_key = Key for the tag (i.e. env:tag_value)

    tag_value = Value for the tag (i.e. tag_key:vsphere)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    czid = get_czid_by_name(url,username,password,czname)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/zones/{1}&#39;.format(api_url_base,czid)
    data =  {
              &#34;name&#34;: czname,
              &#34;tags&#34;: [
                {
                  &#34;key&#34;: tag_key,
                  &#34;value&#34;: tag_value
                }
              ]
            }
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#39;Successfully Tagged Cloud Zone&#39;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def delete_cloudzone(url,username,password,czname):
    &#34;&#34;&#34;
    Delete Cloud Zone

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    czname = Cloud Zone Name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    czid = get_czid_by_name(url,username,password,czname)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/zones/{1}&#39;.format(api_url_base,czid)
    response = requests.delete(api_url, headers=headers, verify=False)
    if response.status_code == 204:
        print(&#39;Successfully Deleted Cloud Zone: &#39; + czname)
        return &#39;Successfully Deleted Cloud Zone: &#39; + czname
    else:
        print(response.status_code)
        return response.status_code

def delete_cloudaccount(url,username,password,ca_name):
    &#34;&#34;&#34;
    Delete Cloud Account

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    ca_name = Cloud Account Name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    ca_json = get_ca_by_name(url,username,password,czname)
    ca_id = ca_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/zones/{1}&#39;.format(api_url_base,ca_id)
    response = requests.delete(api_url, headers=headers, verify=False)
    if response.status_code == 204:
        print(&#39;Successfully Deleted Cloud Account: &#39; + czname)
        return &#39;Successfully Deleted Cloud Account: &#39; + czname
    else:
        print(response.status_code)
        return response.status_code

######Projects######
def create_project(url,username,password,name):
    &#34;&#34;&#34;
    Create a Project

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    name = Name of the Project
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/projects&#39;.format(api_url_base)
    data =  {
              &#34;administrators&#34;: [],
              &#34;members&#34;: [],
              &#34;operationTimeout&#34;: 0,
              &#34;sharedResources&#34;: &#34;true&#34;,
              &#34;name&#34;: name,
              &#34;description&#34;: &#34;Project for &#34; + name
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        print(&#39;Successfully Created Project&#39;)
        return json_data[&#39;id&#39;]
    else:
        print(response.status_code)
        return response.status_code

def get_proj_by_name(url,username,password,projname):
    &#34;&#34;&#34;
    Get Project by Name

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    projname: Name of the Project to search for
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/projects&#39;.format(api_url_base,projname)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            proj_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if proj_name == projname:
                print(&#34;Found Project: &#34; + projname)
                proj_id = json_data[&#39;content&#39;][n]
                return proj_id
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For Project: &#34; + projname)
                break
    else:
        print(response.status_code)
        return response.status_code

def add_member_to_project(url,username,password,projname,member_email):
    &#34;&#34;&#34;
    Add a member to a Project

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    projname = Project you want to add the user to

    member_email = email of the user you want to add to the project
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    proj_json = get_proj_by_name(url,username,password,projname)
    proj_id = proj_json[&#39;id&#39;]
    proj_members = proj_json[&#39;members&#39;]
    member_len = (len(proj_members))
    new_member = {&#34;email&#34;: member_email,&#34;type&#34;: &#34;user&#34;}
    payload = []
    if member_len == 0:
        payload.append(new_member)
    else:
        n = 0
        end = member_len - 1
        while True:
            if n &lt;= end:
                payload.append(proj_members[n])
                n = n + 1
            elif n &gt; end:
                break
        payload.append(new_member)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/projects/{1}&#39;.format(api_url_base,proj_id)
    data =  {
              &#34;members&#34;: payload
            }
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#34;Successfully added &#34; + member_email + &#34; to Project as member&#34;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def add_admin_to_project(url,username,password,projname,admin_email):
    &#34;&#34;&#34;
    Add and admin to the Project

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    projname = Provide name of project you want to add Admin to

    admin_email: Email of the admin you want to add (admins can manage a project)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username,password)
    proj_json = get_proj_by_name(url,username,password,projname)
    proj_id = proj_json[&#39;id&#39;]
    proj_admins = proj_json[&#39;administrators&#39;]
    admin_len = (len(proj_admins))
    new_admin = {&#34;email&#34;: admin_email,&#34;type&#34;: &#34;user&#34;}
    payload = []
    if admin_len == 0:
        payload.append(new_admin)
    else:
        n = 0
        end = admin_len - 1
        while True:
            if n &lt;= end:
                payload.append(proj_admins[n])
                n = n + 1
            elif n &gt; end:
                break
        payload.append(new_admin)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/projects/{1}&#39;.format(api_url_base,proj_id)
    data =  {
              &#34;administrators&#34;: payload
            }
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#34;Successfully added &#34; + admin_email + &#34; to Project as admin&#34;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def add_group_member_to_project(url,username,password,projname,group_email):
    &#34;&#34;&#34;
    Add a group to a Project

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    projname = Provide name of project you want to add group members to

    group_email = Email of the group you want to add (e.g. - vRA-All-Services-Users@acme.local)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    proj_json = get_proj_by_name(url,username,password,projname)
    proj_id = proj_json[&#39;id&#39;]
    proj_members = proj_json[&#39;members&#39;]
    member_len = (len(proj_members))
    new_member = {&#34;email&#34;: group_email,&#34;type&#34;: &#34;group&#34;}
    payload = []
    if member_len == 0:
        payload.append(new_member)
    else:
        n = 0
        end = member_len - 1
        while True:
            if n &lt;= end:
                payload.append(proj_members[n])
                n = n + 1
            elif n &gt; end:
                break
        payload.append(new_member)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/projects/{1}&#39;.format(api_url_base,proj_id)
    data =  {
              &#34;members&#34;: payload
            }
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#34;Successfully added &#34; + group_email + &#34; to Project as member&#34;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def add_group_admin_to_project(url,username,password,projname,group_email):
    &#34;&#34;&#34;
    Add group admin to a Project

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    projname = Provide name of project to add the admin group

    group_email: Email of the group you want to add (i.e. - vRA-All-Services-admins@acme.local

    &#34;&#34;&#34;


    api_url_base = set_bas_url(url)
    access_key = get_token(url,username,password)
    proj_json = get_proj_by_name(url,username,password,projname)
    proj_id = proj_json[&#39;id&#39;]
    proj_admins = proj_json[&#39;administrators&#39;]
    admin_len = (len(proj_admins))
    new_admin = {&#34;email&#34;: group_email,&#34;type&#34;: &#34;group&#34;}
    payload = []
    if admin_len == 0:
        payload.append(new_admin)
    else:
        n = 0
        end = admin_len - 1
        while True:
            if n &lt;= end:
                payload.append(proj_admins[n])
                n = n + 1
            elif n &gt; end:
                break
        payload.append(new_admin)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/projects/{1}&#39;.format(api_url_base,proj_id)
    data =  {
              &#34;administrators&#34;: payload
            }
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#34;Successfully added &#34; + group_email + &#34; to Project as admin&#34;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def add_cloudzone_to_project(url,username,password,projname,czname,priority=None,store_limit=None,cpu_limit=None,mem_limit=None,max_num=None):
    &#34;&#34;&#34;
    Add CloudZone to a Project, once the CloudZone is added that Project can then consume resources in that CloudZone
    via Cloud Templates and Code Stream Pipelines.

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    projname = Provide name of a project you want to add the CloudZone

    czname = Name of CloudZone to Add (e.g. - &#34;AWS-Cloud-Account / us-west-1&#34;)

    priority = 0 is the highest

    store_limit = Max amount of storage that the cloud zone can consume in this project(default=0, vSphere Cloud Zone only)

    cpu_limit = Max number of virtual CPUs that the cloud zone can consume in this project(default=0, unlimited)

    mem_limit = Maximum amount of memory (MB) that the cloud zone can consume in this project(default=0, unlimited)

    max_num = Maximum amount of instances that the cloud zone can deploy in this project(default=0, unlimited)

    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username,password)
    proj_json = get_proj_by_name(url,username,password,projname)
    proj_id = proj_json[&#39;id&#39;]
    proj_zones = proj_json[&#39;zones&#39;]
    zone_len = (len(proj_zones))
    czid = get_czid_by_name(url,username,password,czname)
    if priority is None:
        priority = 0
    if store_limit is None:
        store_limit = 0
    if cpu_limit is None:
        cpu_limit = 0
    if mem_limit is None:
        mem_limit = 0
    if max_num is None:
        max_num = 0
    new_zone = {&#34;storageLimitGB&#34;: store_limit,&#34;cpuLimit&#34;: cpu_limit,&#34;memoryLimitMB&#34;: mem_limit,&#34;zoneId&#34;: czid,&#34;maxNumberInstances&#34;: max_num,&#34;priority&#34;: priority}
    payload = []
    if zone_len == 0:
        payload.append(new_zone)
    else:
        n = 0
        end = zone_len - 1
        while True:
            if n &lt;= end:
                payload.append(proj_zones[n])
                n = n + 1
            elif n &gt; end:
                break
        payload.append(new_zone)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/projects/{1}&#39;.format(api_url_base,proj_id)
    data =  {
              &#34;zoneAssignmentConfigurations&#34;: payload
            }
    print(data)
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#34;Successfully added Cloud Zone &#34; + czname + &#34; to Project&#34;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def enable_tf_on_project(url,username,password,projname):
    &#34;&#34;&#34;
    Enable Terraform Service on a Project

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    projname: Provide name of a Project to add the Terraform service
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    proj_json = get_proj_by_name(url,username,password,projname)
    proj_id = proj_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}project-service/api/projects/{1}&#39;.format(api_url_base,proj_id)
    data =  {
              &#34;properties&#34;: {
                 &#34;__allowTerraformCloudzoneMapping&#34;: &#34;true&#34;
              }
            }
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#34;Successfully enabled Terraform Service on project: &#34; + projname)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def disable_tf_on_project(url,username,password,projname):
    &#34;&#34;&#34;
    Disable Terraform on Project

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    projname = Provide name of a Project to remove the Terraform service
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    proj_json = get_proj_by_name(url,username,password,projname)
    proj_id = proj_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}project-service/api/projects/{1}&#39;.format(api_url_base,proj_id)
    data =  {
              &#34;properties&#34;: {
              }
            }
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#34;Successfully disabled Terraform Service on project: &#34; + projname)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def remove_all_cz_from_project(url,username,password,projname):
    &#34;&#34;&#34;
    Removes all CLoud Zones from project

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    proj_name = Provide name of a Project which to remove all Cloud Zones
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    proj_json = get_proj_by_name(url,username,password,projname)
    proj_id = proj_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}project-service/api/projects/{1}&#39;.format(api_url_base,proj_id)
    data =  {
              &#34;zoneAssignmentConfigurations&#34;: []
            }
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#34;Removed ALL Cloud Zones from project: &#34; + projname)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def delete_project(url,username,password,projname):
    &#34;&#34;&#34;
    Delete Project

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    proj_name = Provide name of a Project to Delete
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    proj_json = get_proj_by_name(url,username,password,projname)
    proj_id = proj_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/projects/{1}&#39;.format(api_url_base,proj_id)
    response = requests.delete(api_url, headers=headers, verify=False)
    if response.status_code == 204:
        print(&#39;Successfully Deleted Project: &#39; + projname)
        return &#39;Successfully Deleted Project: &#39; + projname
    else:
        print(response.status_code)
        return response.status_code

######Flavor Mappings######
def get_cloud_regionid_by_name(url,username,password,region_name):
    &#34;&#34;&#34;
    Get Cloud Region Id for Further Configurations

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    region_name = Provide a name of Region to search for

    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/regions&#39;.format(api_url_base,region_name)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            reg_name = json_data[&#39;content&#39;][n][&#39;externalRegionId&#39;]
            if reg_name == region_name:
                print(&#34;Found Cloud Zone: &#34; + region_name)
                reg_id = json_data[&#39;content&#39;][n][&#39;id&#39;]
                return reg_id
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For Cloud Zone: &#34; + region_name)
                return &#34;No Match Found For Cloud Zone: &#34; + region_name
                break
    else:
        print(response.status_code)
        return response.status_code

def create_cloud_flavor(url,username,password,flavor_name,mapping_name,cloud_instance_name,region_name):
    &#34;&#34;&#34;
    Create Cloud Flavor
    Abstracts cloud images and assigns a size value to them (e.g. - small, medium, large)

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    flavor_name = Provide a name for the Flavor(e.g. - small, medium, etc.)

    size_name = Name

    cloud_size_name = Name of Cloud Size (e.g.- AWS: t2.small , Azure: Standard_B1ms, vSphere: 2:4 - CPU:MEM)

    region_name = Cloud Region (e.g. - Azure: eastus)

    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username,password)
    reg_id = get_cloud_regionid_by_name(url,username,password,region_name)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/flavor-profiles&#39;.format(api_url_base)
    data =  {
                &#34;name&#34;: flavor_name,
                &#34;flavorMapping&#34;: {
                    mapping_name: {
                        &#34;name&#34;: cloud_instance_name
                    }
                },
                &#34;regionId&#34;: reg_id
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        print(&#39;Successfully Created Cloud Flavor&#39;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def get_flavor_by_name(url,username,password,flavor_name):
    &#34;&#34;&#34;
    Get Flavor by name for further configurations

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    flavor_name = Name of the Flavor Mapping
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/flavor-profiles&#39;.format(api_url_base,flavor_name)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            flav_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if flav_name == flavor_name:
                print(&#34;Found Flavor Mapping: &#34; + flavor_name)
                return json_data[&#39;content&#39;][n]
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For Flavor Mapping: &#34; + flavor_name)
                return &#34;No Match Found For Flavor Mapping: &#34; + flavor_name
                break
    else:
        print(response.status_code)
        return response.status_code

def update_cloud_flavor(url,username,password,flavor_name,mapping_name,cloud_instance_name):
    &#34;&#34;&#34;
    Update Cloud Flavor

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    flavor_name = Name of the Flavor Mapping (i.e. aws)

    mapping_name = The name that displays in Cloud Assembly for the flavor (i.e.Small)

    cloud_instance_name = The name if the instance type from the public cloud (i.e. t2.small)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username,password)
    flav_json = get_flavor_by_name(url,username,password,flavor_name)
    flav_id = flav_json[&#39;id&#39;]
    current_flavors = flav_json[&#39;flavorMappings&#39;][&#39;mapping&#39;]
    a = json.dumps(current_flavors)
    a = a[1:-1]
    new_flavor =  {mapping_name:{&#34;name&#34;: cloud_instance_name}}
    b = json.dumps(new_flavor)
    b = b[1:-1]
    combined = a + &#34;,&#34; + b
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/flavor-profiles/{1}&#39;.format(api_url_base,flav_id)
    payload = &#34;{&#34; + &#39;&#34;&#39; + &#34;flavorMapping&#34; + &#39;&#34;&#39; + &#34;:&#34; &#34; {&#34;+ combined + &#34;}}&#34;
    data = json.loads(payload)
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#39;Successfully Updated Cloud Flavor&#39;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def create_vsphere_flavor(url,username,password,flavor_name,mapping_name,cpu_count,mem_count,region_name):
    &#34;&#34;&#34;
    Create vSphere Flavor
    vSphere Flavor is a size of an image, t-shirt sizing&#34;

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    flavor_name = Name of the Flavor Mapping (i.e. vsphere)

    mapping_name = The name that displays in Cloud Assembly for the flavor (i.e.Small)

    cpu_count = number of CPUs assigned using this flavor (i.e. 2)

    mem_count = amount of memory assigned using this flavor in GB (i.e. 4)

    region_name = The datacenter id for the Cloud Account (i.e. Datacenter:datacenter-2)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username,password)
    reg_id = get_cloud_regionid_by_name(url,username,password,region_name)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/flavor-profiles&#39;.format(api_url_base)
    data =  {
                &#34;name&#34;: flavor_name,
                &#34;flavorMapping&#34;: {
                    mapping_name: {
                        &#34;cpuCount&#34;: cpu_count,
                        &#34;memoryInMB&#34;: mem_count
                    }
                },
                &#34;regionId&#34;: reg_id
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        print(&#39;Successfully Created vSphere Flavor&#39;)
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def update_vsphere_flavor(url,username,password,flavor_name,mapping_name,cpu_count,mem_count):
    &#34;&#34;&#34;
    Update vSphere Flavor

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    flavor_name = Name of the Flavor Mapping (i.e. vsphere)

    mapping_name = The name that displays in Cloud Assembly for the flavor (i.e.Small)

    cpu_count = number of CPUs assigned using this flavor (i.e. 2)

    mem_count = amount of memory assigned using this flavor in GB (i.e. 4)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username,password)
    flav_json = get_flavor_by_name(url,username,password,flavor_name)
    flav_id = flav_json[&#39;id&#39;]
    current_flavors = flav_json[&#39;flavorMappings&#39;][&#39;mapping&#39;]
    a = json.dumps(current_flavors)
    a = a[1:-1]
    new_flavor = {mapping_name:{&#34;cpuCount&#34;: cpu_count,&#34;memoryInMB&#34;: mem_count}}
    b = json.dumps(new_flavor)
    b = b[1:-1]
    combined = a + &#34;,&#34; + b
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/flavor-profiles/{1}&#39;.format(api_url_base,flav_id)
    payload = &#34;{&#34; + &#39;&#34;&#39; + &#34;flavorMapping&#34; + &#39;&#34;&#39; + &#34;:&#34; &#34; {&#34;+ combined + &#34;}}&#34;
    data = json.loads(payload)
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#39;Successfully Updated vSphere Flavor&#39;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def delete_flavor_mapping(url,username,password,flavor_name):
    &#34;&#34;&#34;
    Delete Flavor Mapping

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    flavor_name = Flavor name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    flav_json = get_flavor_by_name(url,username,password,flavor_name)
    flav_id = flav_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/flavor-profiles/{1}&#39;.format(api_url_base,flav_id)
    response = requests.delete(api_url, headers=headers, verify=False)
    if response.status_code == 204:
        print(&#39;Successfully Deleted Flavor Mapping: &#39; + flavor_name)
        return &#39;Successfully Deleted Flavor Mapping: &#39; + flavor_name
    else:
        print(response.status_code)
        return response.status_code

######Image Mappings######
def create_image_mapping(url,username,password,profile_name,image_name,image_id,region_name):
    &#34;&#34;&#34;
    Create Image Mapping.
    An image mapping ties a cloud image (AWS = AMI, vSphere = Template) to a Cloud Zone Region

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    profile_name = The name of the image profile (i.e.vsphere-images)

    image_name = The name of the image (i.e. Ubuntu)

    image_id = name of the image instance (i.e. ami-03659409b9c7d0c5f or vsphere-ubuntu-template)

    region_name = The datacenter id for the Cloud Account (i.e. Datacenter:datacenter-2 or eastus or us-west-1)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username,password)
    reg_id = get_cloud_regionid_by_name(url,username,password,region_name)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/image-profiles&#39;.format(api_url_base)
    data =  {
              &#34;name&#34; : profile_name,
              &#34;description&#34;: &#34;Image Profile for &#34; + profile_name,
              &#34;imageMapping&#34; : {
                image_name: {
                  &#34;name&#34;: image_id
                }
              },
              &#34;regionId&#34;: reg_id
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        print(&#34;Successfully Created Image Mapping: &#34; + profile_name)
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def get_image_profile_by_name(url,username,password,profile_name):
    &#34;&#34;&#34;
    Gets image mapping by name and reutns information via json

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    profile_name = The name of the image profile (i.e.vsphere-images)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/image-profiles&#39;.format(api_url_base,profile_name)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            img_prof_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if img_prof_name == profile_name:
                print(&#34;Found Image Mapping: &#34; + profile_name)
                return json_data[&#39;content&#39;][n]
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For Flavor Mapping: &#34; + flavor_name)
                return &#34;No Match Found For Flavor Mapping: &#34; + flavor_name
                break
    else:
        print(response.status_code)
        return response.status_code

def update_image_mapping(url,username,password,profile_name,image_name,image_id):
    &#34;&#34;&#34;
    Updates an existing Image Mapping.

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    profile_name = The name of the image profile (i.e.vsphere-images)

    image_name = The name of the image (i.e. Ubuntu)

    image_id = name of the image instance (i.e. ami-03659409b9c7d0c5f or vsphere-ubuntu-template)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username,password)
    img_json = get_image_profile_by_name(url,username,password,profile_name)
    img_id = img_json[&#39;id&#39;]
    current_image = img_json[&#39;imageMappings&#39;][&#39;mapping&#39;]
    a = json.dumps(current_image)
    a = a[1:-1]
    new_image = {image_name: {&#34;name&#34;: image_id}}
    b = json.dumps(new_image)
    b = b[1:-1]
    combined = a + &#34;,&#34; + b
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/image-profiles/{1}&#39;.format(api_url_base,img_id)
    payload = &#34;{&#34; + &#39;&#34;&#39; + &#34;imageMapping&#34; + &#39;&#34;&#39; + &#34;:&#34; &#34; {&#34;+ combined + &#34;}}&#34;
    data = json.loads(payload)
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#39;Successfully Updated Image Mapping: &#39; + profile_name)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def delete_image_mapping(url,username,password,profile_name):
    &#34;&#34;&#34;
    Delete Image Mapping

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    profile_name = Image Profile Name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    img_json = get_image_profile_by_name(url,username,password,profile_name)
    img_id = img_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/image-profiles/{1}&#39;.format(api_url_base,img_id)
    response = requests.delete(api_url, headers=headers, verify=False)
    if response.status_code == 204:
        print(&#39;Successfully Deleted Flavor Mapping: &#39; + profile_name)
        return &#39;Successfully Deleted Flavor Mapping: &#39; + profile_name
    else:
        print(response.status_code)
        return response.status_code

######Network Profiles######
def create_network_profile(url,username,password,region_name,net_profile_name):
    &#34;&#34;&#34;
    Create Network Profile.

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    net_profile_name = The name of the network profile (i.e.vsphere-networks)

    region_name = The datacenter id for the Cloud Account (i.e. Datacenter:datacenter-2 or eastus or us-west-1)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    reg_id = get_cloud_regionid_by_name(url,username,password,region_name)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/network-profiles&#39;.format(api_url_base)
    data = {
              &#34;isolationType&#34;: &#34;NONE&#34;,
              &#34;tags&#34;: [],
              &#34;customProperties&#34;: {
                &#34;datacenterId&#34;: region_name
              },
              &#34;name&#34;: net_profile_name,
              &#34;regionId&#34;: reg_id
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        print(&#39;Successfully Created Network Profile: &#39; + net_profile_name)
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def get_netprofile_by_name(url,username,password,net_profile_name):
    &#34;&#34;&#34;
    Get existing Network Profile by name and return information via json.

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    net_profile_name = The name of the network profile (i.e.vsphere-networks)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/network-profiles&#39;.format(api_url_base,net_profile_name)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            prof_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if prof_name == net_profile_name:
                print(&#34;Found Network Profile: &#34; + net_profile_name)
                prof_id = json_data[&#39;content&#39;][n]
                return prof_id
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For Network Profile: &#34; + net_profile_name)
                break
    else:
        print(response.status_code)
        return response.status_code

def get_fabric_network_by_name(url,username,password,fabric_net_name):
    &#34;&#34;&#34;
    Get discovered network by name and return information via json.

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    fabric_net_name = The name of the network that was discovered by vRA discover service (i.e.web-network)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/fabric-networks&#39;.format(api_url_base,fabric_net_name)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            net_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if net_name == fabric_net_name:
                print(&#34;Found Frabric Network: &#34; + fabric_net_name)
                fabnet_id = json_data[&#39;content&#39;][n]
                return fabnet_id
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For Frabric Network: &#34; + fabric_net_name)
                break
    else:
        print(response.status_code)
        return response.status_code

def add_network_to_profile(url,username,password,region_name,net_profile_name,fabric_net_name):
    &#34;&#34;&#34;
    Adds a discovered network to an existing Network Profile

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    net_profile_name = The name of the network profile (i.e.vsphere-networks)

    region_name = The datacenter id for the Cloud Account (i.e. Datacenter:datacenter-2 or eastus or us-west-1)

    fabric_net_name = The name of the network that was discovered by vRA discover service (i.e.web-network)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    reg_id = get_cloud_regionid_by_name(url,username,password,region_name)
    prof_json = get_netprofile_by_name(url,username,password,net_profile_name)
    fab_net_json = get_fabric_network_by_name(url,username,password,fabric_net_name)
    fab_net_id = fab_net_json[&#39;id&#39;]
    fab_id = []
    fab_id.append(fab_net_id)
    try:
        current_assigned_networks = prof_json[&#39;_links&#39;][&#39;fabric-networks&#39;][&#39;hrefs&#39;]
        for net in current_assigned_networks:
            net = net[26:]
            fab_id.append(net)
    except:
        print(&#34;Currently no networks assigned&#34;)
    prof_id = prof_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/network-profiles/{1}&#39;.format(api_url_base,prof_id)
    data = {
              &#34;fabricNetworkIds&#34;: fab_id
            }
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        print(&#39;Successfully Added Network to Network Profile: &#39; + net_profile_name)
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def get_cloud_acct_type(url,username,password,caid):
    &#34;&#34;&#34;
    Returns the type of Cloud Account based on id. (used to determine NSX resources)

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    caid = Cloud Account ID
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/cloud-accounts/{1}&#39;.format(api_url_base,caid)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        ca_type = extract_values(json_data,&#39;cloudAccountType&#39;)
        return ca_type
    else:
        return response.status_code

def get_nsxt_fabric_network_by_name(url,username,password,fabric_net_name):
    &#34;&#34;&#34;
    Get discovered NSX-T network by name and return information via json.

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    fabric_net_name = The name of the network that was discovered by vRA discover service (i.e.web-network)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/fabric-networks&#39;.format(api_url_base,fabric_net_name)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            net_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if net_name == fabric_net_name:
                print(&#34;Found Frabric Network: &#34; + fabric_net_name)
                ca_type = get_cloud_acct_type(url,username,password,json_data[&#39;content&#39;][n][&#39;cloudAccountIds&#39;][0])
                if ca_type[0] == &#34;nsxt&#34;:
                    print(&#34;Fabric Network is type NSXT&#34;)
                    fabnet_id = json_data[&#39;content&#39;][n]
                    return fabnet_id
                    break
                elif n &lt; end_n:
                    print(&#34;Frabric Network is not type NSXT&#34;)
                    n = n + 1
                elif n &gt;= end_n:
                    print(&#34;No Match Found For NSXT Frabric Network: &#34; + fabric_net_name)
                    break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For NSXT Frabric Network: &#34; + fabric_net_name)
                break
    else:
        print(response.status_code)
        return response.status_code

def add_nsxt_network_to_profile(url,username,password,region_name,net_profile_name,fabric_net_name):
    &#34;&#34;&#34;
    Adds a discovered NSX-T network to an existing Network Profile

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    net_profile_name = The name of the network profile (i.e.vsphere-networks)

    region_name = The datacenter id for the Cloud Account (i.e. Datacenter:datacenter-2 or eastus or us-west-1)

    fabric_net_name = The name of the network that was discovered by vRA discover service (i.e.web-network)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    reg_id = get_cloud_regionid_by_name(url,username,password,region_name)
    prof_json = get_netprofile_by_name(url,username,password,net_profile_name)
    fab_net_json = get_nsxt_fabric_network_by_name(url,username,password,fabric_net_name)
    fab_net_id = fab_net_json[&#39;id&#39;]
    fab_id = []
    fab_id.append(fab_net_id)
    try:
        current_assigned_networks = prof_json[&#39;_links&#39;][&#39;fabric-networks&#39;][&#39;hrefs&#39;]
        for net in current_assigned_networks:
            net = net[26:]
            fab_id.append(net)
    except:
        print(&#34;Currently no networks assigned&#34;)
    prof_id = prof_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/network-profiles/{1}&#39;.format(api_url_base,prof_id)
    data = {
              &#34;fabricNetworkIds&#34;: fab_id
            }
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        print(&#39;Successfully Added NSXT Network to Network Profile: &#39; + net_profile_name)
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def tag_fabric_network(url,username,password,fabric_net_name,tag_key,tag_value):
    &#34;&#34;&#34;
    Tags a discovered network in vRA.

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    fabric_net_name = The name of the network that was discovered by vRA discover service (i.e.web-network)

    tag_key = The key for the tag (i.e env:tag_value)

    tag_value = Th value for the tag (i.e. tag_key:vsphere)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    fab_net_json = get_fabric_network_by_name(url,username,password,fabric_net_name)
    fab_net_id = fab_net_json[&#39;id&#39;]
    try:
        current_tags = fab_net_json[&#39;tags&#39;]
        new_tag = {&#34;key&#34;: tag_key,&#34;value&#34;: tag_value}
        current_tags.append(new_tag)
        tags = current_tags
    except:
        print(&#34;Currently no tags assigned&#34;)
        tags = []
        new_tag = {&#34;key&#34;: tag_key,&#34;value&#34;: tag_value}
        tags.append(new_tag)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/fabric-networks/{1}&#39;.format(api_url_base,fab_net_id)
    data = {
              &#34;tags&#34;: tags
            }
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        print(&#39;Successfully Tagged Fabric Network: &#39; + fabric_net_name)
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def config_ondemand_sec_groups_vsphere_network_profile(url,username,password,net_profile_name,edge_router_name,t0_router_name):
    &#34;&#34;&#34;
    Configues vSphere network profile for on-demand security groups

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    net_profile_name = The name of the network profile (i.e.vsphere-networks)

    edge_router_name = Name of the edge router in NSX-T

    t0_router_name = Name of the T0 router in NSX-T
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    net_prof_json = get_netprofile_by_name(url,username,password,net_profile_name)
    net_prof_id = net_prof_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/network-profiles/{1}&#39;.format(api_url_base,net_prof_id)
    current_dc_id = net_prof_json[&#39;customProperties&#39;][&#39;datacenterId&#39;]
    edge_router_link = get_nsxt_router_link_by_name(url,username,password,edge_router_name)
    t0_router_link = get_nsxt_router_link_by_name(url,username,password,t0_router_name)
    data = {
            &#34;isolationType&#34;: &#34;SECURITY_GROUP&#34;,
            &#34;customProperties&#34;: {
                &#34;datacenterId&#34;: current_dc_id,
                &#34;edgeClusterRouterStateLink&#34;: edge_router_link,
                &#34;tier0LogicalRouterStateLink&#34;: t0_router_link
            }
           }
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        print(&#39;Successfully Configured On-Demand Security Group: &#39; + net_profile_name)
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def get_sec_group_by_name(url,username,password,secgroup_name):
    &#34;&#34;&#34;
    Get discovered security group by name and return information via json.

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    secgroup_name = The name of the existing security group (i.e.web-security)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/security-groups&#39;.format(api_url_base,secgroup_name)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            sg_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if sg_name == secgroup_name:
                print(&#34;Found Security Group: &#34; + secgroup_name)
                sg_id = json_data[&#39;content&#39;][n][&#39;id&#39;]
                return sg_id
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For Security Group: &#34; + secgroup_name)
                break
    else:
        print(response.status_code)
        return response.status_code

def add_sec_group_vsphere_net_profile(url,username,password,net_profile_name,secgroup_name):
    &#34;&#34;&#34;
    Adds discovered security group to a network profile.

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    net_profile_name = The name of the network profile (i.e.vsphere-networks)

    secgroup_name = The name of the existing security group (i.e.web-security)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    net_prof_json = get_netprofile_by_name(url,username,password,net_profile_name)
    net_prof_id = net_prof_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/network-profiles/{1}&#39;.format(api_url_base,net_prof_id)
    try:
        current_secgroups = net_prof_json[&#39;_links&#39;][&#39;security-groups&#39;][&#39;hrefs&#39;]
        sec_groups = []
        for x in current_secgroups:
            x = x[26:]
            sec_groups.append(x)
        new_sec_group = get_sec_group_by_name(url,username,password,secgroup_name)
        sec_groups.append(new_sec_group)
    except:
        print(&#34;Currently no Security Groups assigned&#34;)
        sec_groups = []
        new_sec_group = get_sec_group_by_name(url,username,password,secgroup_name)
        sec_groups.append(new_sec_group)
    data = {
              &#34;securityGroupIds&#34;: sec_groups
            }
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        print(&#39;Successfully Added Security Group: &#39; + secgroup_name)
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def delete_netprofile(url,username,password,net_profile_name):
    &#34;&#34;&#34;
    Delete Network Profile

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    net_profile_name = Network Profile Name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    net_json = get_netprofile_by_name(url,username,password,net_profile_name)
    net_id = net_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/network-profiles/{1}&#39;.format(api_url_base,net_id)
    response = requests.delete(api_url, headers=headers, verify=False)
    if response.status_code == 204:
        print(&#39;Successfully Deleted Network Profile: &#39; + net_profile_name)
        return &#39;Successfully Deleted Network profile: &#39; + net_profile_name
    else:
        print(response.status_code)
        return response.status_code

######Storage Profiles######
def get_vsphere_datastore_by_name(url,username,password,datastore_name):
    &#34;&#34;&#34;
    Get vsphere datastore by name and return information via json.

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    datastore_name = The name of the datastore (i.e.sc2c01vsan01)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/fabric-vsphere-datastores&#39;.format(api_url_base,datastore_name)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            ds_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if ds_name == datastore_name:
                print(&#34;Found vSphere Datastore: &#34; + datastore_name)
                ds_id = json_data[&#39;content&#39;][n]
                return ds_id
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For vSphere Datastore: &#34; + datastore_name)
                break
    else:
        print(response.status_code)
        return response.status_code

def get_storage_policy_id_by_name(url,username,password,policy_name):
    &#34;&#34;&#34;
    Get storage policy id by name and return information via json.

    Arguments:


    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    policy_name = The name of the storage policy (i.e. &#34;vSAN Default Storage Policy&#34;)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/fabric-vsphere-storage-policies&#39;.format(api_url_base,policy_name)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            sp_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if sp_name == policy_name:
                print(&#34;Found vSphere Storage Polcy: &#34; + policy_name)
                sp_id = json_data[&#39;content&#39;][n][&#39;id&#39;]
                return sp_id
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For vSphere Storage Policy: &#34; + policy_name)
                break
    else:
        print(response.status_code)
        return response.status_code

def get_storage_profile_by_name(url,username,password,storage_profile_name):
    &#34;&#34;&#34;
    Get Storage Profile by Name and return json information

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    storage_profile_name = Storage Profile Name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/storage-profiles&#39;.format(api_url_base,policy_name)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            sp_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if sp_name == storage_profile_name:
                print(&#34;Found Storage Profile: &#34; + storage_profile_name)
                sp_id = json_data[&#39;content&#39;][n]
                return sp_id
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For Storage Profile: &#34; + storage_profile_name)
                break
    else:
        print(response.status_code)
        return response.status_code

def create_vsphere_storage_profile(url,username,password,name,region_name,datastore_name,encrypted=&#34;false&#34;,sharelevel=&#34;normal&#34;,diskmode=&#34;independent-persistent&#34;,tag_key=None,iops_limit=None,tag_value=None,shares=&#34;1000&#34;,provision_type=&#34;thin&#34;,default=&#34;false&#34;,disktype=&#34;standard&#34;,policy_name=None):
    &#34;&#34;&#34;
    Creates a vSphere Storage Profile

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    name = Name of the Storage Profile

    region_name = Name of the region this profile is attached (i.e Datacenter:datacenter-2)

    datastor_name = Name of the datastore to assign to profile

    encrypted = is datastore encrypted (true or false(default))

    sharelevel = Sets the share level (unspecified / low / normal(default) / high / custom)

    diskmode = Sets the disk mode for the profile (dependent / independent-persistent(default) / independent-nonpersistent)

    tag_key = Key for the tag (i.e. env:tag_value)

    tag_value = Value for the tag (i.e. tag_key:vsphere)

    iops_limit = Sets the IOPs limit for the Storage profile (if not set value is set to unlimited)

    shares = Sets the shares value for the storage profile (default is 1000)

    provision_type = Sets the provisioning type for the storage profile (unspecified / thin / thick / eagerZeroedThick)

    default = Is this the default profile for the region (true / false (default))

    disk_type = Type of disk for this profile (standard (default) / fcd)

    policy_name = The name of the storage policy from vCenter to use for this profile (if argument not added then datastore default policy is applied)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    reg_id = get_cloud_regionid_by_name(url,username,password,region_name)
    if tag_key != None:
        if tag_value != None:
            tag_prep = {&#34;key&#34;: tag_key,&#34;value&#34;: tag_value}
            tag = []
            tag.append(tag_prep)
    else:
        tag = []
    ds_json = get_vsphere_datastore_by_name(url,username,password,datastore_name)
    ds_id = ds_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/storage-profiles-vsphere&#39;.format(api_url_base)
    payload = {
              &#34;supportsEncryption&#34;: encrypted,
              &#34;sharesLevel&#34;: sharelevel,
              &#34;description&#34;: &#34;vSphere Storage&#34;,
              &#34;diskMode&#34;: diskmode,
              &#34;tags&#34;: tag,
              &#34;shares&#34;: shares,
              &#34;provisioningType&#34;: provision_type,
              &#34;regionId&#34;: reg_id,
              &#34;name&#34;: name,
              &#34;defaultItem&#34;: default,
              &#34;diskType&#34;: disktype,
              &#34;datastoreId&#34;: ds_id
            }
    if policy_name != None:
        policy_id = get_storage_policy_id_by_name(url,username,password,policy_name)
        a = json.dumps(payload)
        a = a[1:-1]
        policy = {&#34;storagePolicyId&#34;: policy_id}
        b = json.dumps(policy)
        b = b[1:-1]
        combined = a + &#34;,&#34; + b
        payload = &#34;{&#34; + combined + &#34;}&#34;
        payload = json.loads(payload)
    if iops_limit != None:
        c = json.dumps(payload)
        c = c[1:-1]
        iops = {&#34;limitIops&#34;: iops_limit}
        d = json.dumps(iops)
        d = d[1:-1]
        combined = c + &#34;,&#34; + d
        payload = &#34;{&#34; + combined + &#34;}&#34;
        payload = json.loads(payload)
    data = payload
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        print(&#39;Successfully Created vSphere Storage Profile&#39;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def create_aws_storage_profile(url,username,password,name,region_name,encrypted=&#34;false&#34;,devicetype=&#34;ebs&#34;,volumetype=&#34;standard&#34;,tag_key=None,iops_limit=None,tag_value=None,default=&#34;false&#34;):
    &#34;&#34;&#34;
    Creates a AWS Storage Profile

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    name = Name of the Storage Profile

    region_name = Name of the region this profile is attached (i.e us-west-1)

    encrypted = Is datastore encrypted (true or false(default))

    devicetype = The type of storage device to use (ebs / instance-store)

    volumetype = The type of volume (gp2 / io1 / sc1 / st1 / standard)

    tag_key = The key for the tag (i.e env:tag_value)

    tag_value = Th value for the tag (i.e. tag_key:aws)

    iops_limit = Sets the IOPs limit for the Storage profile (if not set value is set to unlimited)

    default = Is this the default profile for the region (true / false (default))
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    reg_id = get_cloud_regionid_by_name(url,username,password,region_name)
    if tag_key != None:
        if tag_value != None:
            tag_prep = {&#34;key&#34;: tag_key,&#34;value&#34;: tag_value}
            tag = []
            tag.append(tag_prep)
    else:
        tag = []
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/storage-profiles-aws&#39;.format(api_url_base)
    payload = {
                  &#34;deviceType&#34;: devicetype,
                  &#34;volumeType&#34;: volumetype,
                  &#34;supportsEncryption&#34;: encrypted,
                  &#34;regionId&#34;: reg_id,
                  &#34;name&#34;: name,
                  &#34;description&#34;: &#34;AWS Storage Profile&#34;,
                  &#34;defaultItem&#34;: default,
                  &#34;tags&#34;: tag
                }
    if iops_limit != None:
        c = json.dumps(payload)
        c = c[1:-1]
        iops = {&#34;limitIops&#34;: iops_limit}
        d = json.dumps(iops)
        d = d[1:-1]
        combined = c + &#34;,&#34; + d
        payload = &#34;{&#34; + combined + &#34;}&#34;
        payload = json.loads(payload)
    data = payload
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        print(&#39;Successfully Created AWS Storage Profile&#39;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def create_azure_storage_profile(url,username,password,name,region_name,encrypted=&#34;false&#34;,disktype=&#34;Standard_LRS&#34;,diskcaching=&#34;None&#34;,oscaching=&#34;None&#34;,tag_key=None,tag_value=None,default=&#34;false&#34;):
    &#34;&#34;&#34;
    Creates a Azure Storage Profile

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    name = Name of the Storage Profile

    region_name = Name of the region this profile is attached (i.e us-west-1)

    encrypted = Is datastore encrypted (true or false(default))

    disktype = The type of storage device to use (Standard_LRS / Premium_LRS)

    diskcaching = Cache the data disk? (None / ReadOnly / ReadWrite)

    oscaching = Cache the OS disk? (None / ReadOnly / ReadWrite)

    tag_key = The key for the tag (i.e env:tag_value)

    tag_value = Th value for the tag (i.e. tag_key:azure)

    default = Is this the default profile for the region (true / false (default))
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    reg_id = get_cloud_regionid_by_name(url,username,password,region_name)
    if tag_key != None:
        if tag_value != None:
            tag_prep = {&#34;key&#34;: tag_key,&#34;value&#34;: tag_value}
            tag = []
            tag.append(tag_prep)
    else:
        tag = []
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/storage-profiles-azure&#39;.format(api_url_base)
    data = {
             &#34;supportsEncryption&#34;: encrypted,
             &#34;regionId&#34;: reg_id,
             &#34;name&#34;: name,
             &#34;description&#34;: &#34;Azure Storage Profile&#34;,
             &#34;defaultItem&#34;: default,
             &#34;diskType&#34;: disktype,
             &#34;dataDiskCaching&#34;: diskcaching,
             &#34;osDiskCaching&#34;: oscaching,
             &#34;tags&#34;: tag
           }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        print(&#39;Successfully Created Azure Storage Profile&#39;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code

######Integrations######
def create_actions_content_source(url,username,password,name,int_name,proj_name,repo,branch,path):
    &#34;&#34;&#34;
    Creates an action content source on a github integration

    Arguments:


    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    name = Name of the content source (i.e. ABC Actions)

    int_name = Name of the integration (i.e. ABC GitHub Integration)

    proj_name = Name of vRA Project to associate content source

    repo = Name of the github repository

    branch = Name of branch in repo (i.e. master)

    path = path to folder of actions (i.e actions)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    proj_json = get_proj_by_name(url,username,password,proj_name)
    proj_id = proj_json[&#39;id&#39;]
    int_id = get_integration_by_name(url,username,password,int_name)
    api_url = &#39;{0}content/api/sources&#39;.format(api_url_base)
    data =  {
              &#34;name&#34;: name,
              &#34;typeId&#34;: &#34;com.github&#34;,
              &#34;syncEnabled&#34; : &#34;true&#34;,
              &#34;projectId&#34; : proj_id,
              &#34;config&#34;: {
                &#34;integrationId&#34; : int_id,
                &#34;repository&#34; : &#34;mcclanc/vra8-content&#34;,
                &#34;path&#34; : path,
                &#34;branch&#34; : &#34;master&#34;,
                &#34;contentType&#34; : &#34;abx_scripts&#34;
              }
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        print(&#39;Successfully Created Actions Content Source&#39;)
        return &#39;Successfully Created Actions Content Source&#39;
    else:
        print(response.status_code)
        return response.status_code

def create_blueprint_content_source(url,username,password,name,int_name,proj_name,repo,branch,path):
    &#34;&#34;&#34;
    Creates a cloud template content source on a github integration

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    name = Name of the content source (i.e. ABC Actions)

    int_name = Name of the integration (i.e. ABC GitHub Integration)

    proj_name = Name of vRA Project to associate content source

    repo = Name of the github repository

    branch = Name of branch in repo (i.e. master)

    path = Folder name storing cloud templates in repo (i.e templates)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    proj_json = get_proj_by_name(url,username,password,proj_name)
    proj_id = proj_json[&#39;id&#39;]
    int_id = get_integration_by_name(url,username,password,int_name)
    api_url = &#39;{0}content/api/sources&#39;.format(api_url_base)
    data =  {
              &#34;name&#34;: name,
              &#34;typeId&#34;: &#34;com.github&#34;,
              &#34;syncEnabled&#34; : &#34;true&#34;,
              &#34;projectId&#34; : proj_id,
              &#34;config&#34;: {
                &#34;integrationId&#34; : int_id,
                &#34;repository&#34; : &#34;mcclanc/vra8-content&#34;,
                &#34;path&#34; : path,
                &#34;branch&#34; : &#34;master&#34;,
                &#34;contentType&#34; : &#34;blueprint&#34;
              }
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        print(&#39;Successfully Created Blueprint Content Source&#39;)
        return &#39;Successfully Created Blueprint Content Source&#39;
    else:
        print(response.status_code)
        return response.status_code

def delete_storage_profile(url,username,password,storage_profile_name):
    &#34;&#34;&#34;
    Delete Storage Profile

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    storage_profile_name = Storage Profile Name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    sp_json = get_storage_profile_by_name(url,username,password,storage_profile_name)
    sp_id = sp_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/storage-profiles/{1}&#39;.format(api_url_base,sp_id)
    response = requests.delete(api_url, headers=headers, verify=False)
    if response.status_code == 204:
        print(&#39;Successfully Deleted Storage Profile: &#39; + storage_profile_name)
        return &#39;Successfully Deleted Storage Profile: &#39; + storage_profile_name
    else:
        print(response.status_code)
        return response.status_code

######Blueprint Version and Release######
def get_template_by_name(url,username,password,template_name):
    &#34;&#34;&#34;
    Finds the cloud template by name and returns information via json

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    template_name = Name of the cloud template to find
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}blueprint/api/blueprints&#39;.format(api_url_base)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            templt_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if templt_name == template_name:
                print(&#34;Found Cloud Template: &#34; + template_name)
                template_id = json_data[&#39;content&#39;][n]
                return template_id
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For Cloud Template: &#34; + template_name)
                break
    else:
        print(response.status_code)
        return response.status_code

def create_template_version(url,username,password,template_name,version,release=&#34;false&#34;,change_log=None):
    &#34;&#34;&#34;
    Creates a version of the cloud template

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    template_name = Name of the cloud template to find

    version = version for the template (i.e. 1.1)

    release = Release the version to the Service Broker catalog (true / false (default))

    change_log = Description of changes to template (if not included the change log is left blank)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    template_json = get_template_by_name(url,username,password,template_name)
    template_id = template_json[&#39;id&#39;]
    api_url = &#39;{0}blueprint/api/blueprints/{1}/versions&#39;.format(api_url_base,template_id)
    if change_log == None:
        change_log = &#34;&#34;
    data =  {
              &#34;changeLog&#34;: change_log,
              &#34;description&#34;: &#34;Created version &#34; + version + &#34; of Template&#34;,
              &#34;release&#34;: release,
              &#34;version&#34;: version
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        print(&#39;Successfully Created Version of Cloud Template&#39;)
        return &#39;Successfully Created Version of Cloud Template&#39;
    else:
        print(response.status_code)
        return response.status_code

def release_template_version(url,username,password,template_name,version):
    &#34;&#34;&#34;
    Releases a version of the cloud template to the Service Broker catalog

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    template_name = Name of the cloud template to find

    version = version for the template (i.e. 1.1)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    template_json = get_template_by_name(url,username,password,template_name)
    template_id = template_json[&#39;id&#39;]
    api_url = &#39;{0}blueprint/api/blueprints/{1}/versions/{2}/actions/release&#39;.format(api_url_base,template_id,version)
    response = requests.post(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        print(&#39;Successfully Released Version of Cloud Template to Catalog&#39;)
        return &#39;Successfully Released Version of Cloud Template to Catalog&#39;
    else:
        print(response.status_code)
        return response.status_code

def delete_template(url,username,password,template_name):
    &#34;&#34;&#34;
    Delete Cloud Template

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    template_name = Cloud Template Name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    temp_json = get_template_by_name(url,username,password,template_name)
    temp_id = temp_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}blueprint/api/blueprints/{1}&#39;.format(api_url_base,temp_id)
    response = requests.delete(api_url, headers=headers, verify=False)
    if response.status_code == 204:
        print(&#39;Successfully Deleted Cloud Template: &#39; + template_name)
        return &#39;Successfully Deleted Cloud Template: &#39; + template_name
    else:
        print(response.status_code)
        return response.status_code

##########Service Broker##########
def create_sb_content_source(url,username,password,name,proj_name,content_type):
    &#34;&#34;&#34;
    Creates Content Source in Service Broker

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    name = Content Source name

    proj_name = vRA Project name

    content_type = PIPELINE / TEMPLATE / ABX / VRO
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    proj_json = get_proj_by_name(url,username,password,proj_name)
    proj_id = proj_json[&#39;id&#39;]
    if content_type == &#34;PIPELINE&#34;:
        content_type = &#34;com.vmw.codestream&#34;
    if content_type == &#34;TEMPLATE&#34;:
        content_type = &#34;com.vmw.blueprint&#34;
    if content_type == &#34;ABX&#34;:
        content_type = &#34;com.vmw.abx.actions&#34;
    if content_type == &#34;VRO&#34;:
        content_type = &#34;com.vmw.vro.workflow&#34;
    api_url = &#39;{0}catalog/api/admin/sources&#39;.format(api_url_base)
    data =  {
              &#34;config&#34;: {
                &#34;sourceProjectId&#34;: proj_id
              },
              &#34;typeId&#34;: content_type,
              &#34;name&#34;: name
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        print(&#39;Successfully Created Service Broker Content Source: &#39; + name)
        return &#39;Successfully Created Actions Content Source: &#39; + name
    else:
        print(response.status_code)
        return response.status_code

def get_sb_content_source_by_name(url,username,password,content_source_name):
    &#34;&#34;&#34;
    Finds the Service Broker content source by name and returns information via json

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    content_source_name = The name used to create the content source in Service Broker
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}catalog/api/admin/sources&#39;.format(api_url_base)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;numberOfElements&#39;]
        end_n = end_n - 1
        while True:
            source_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if source_name == content_source_name:
                print(&#34;Found Content Source: &#34; + content_source_name)
                source_id = json_data[&#39;content&#39;][n]
                return source_id
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For Frabric Network: &#34; + content_source_name)
                break
    else:
        print(response.status_code)
        return response.status_code

def create_sb_content_source(url,username,password,proj_name,content_source_name):
    &#34;&#34;&#34;
    Adds Entitlement to the Project for a Service Broker content source

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    proj_name = vRA Project name

    content_source_name = The name used to create the content source in Service Broker
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    proj_json = get_proj_by_name(url,username,password,proj_name)
    proj_id = proj_json[&#39;id&#39;]
    cs_json = get_sb_content_source_by_name(url,username,password,content_source_name)
    cs_id = cs_json[&#39;id&#39;]
    api_url = &#39;{0}catalog/api/admin/entitlements&#39;.format(api_url_base)
    data =  {
              &#34;projectId&#34;: proj_id,
              &#34;definition&#34;: {
                &#34;id&#34;: cs_id,
                &#34;sourceName&#34;: content_source_name,
                &#34;type&#34;: &#34;CatalogSourceIdentifier&#34;
              }
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        print(&#39;Successfully Entitled Content Source: &#39; + content_source_name)
        return &#39;Successfully Entitled Content Source: &#39; + content_source_name
    else:
        print(response.status_code)
        return response.status_code

def delete_sb_content_source(url,username,password,content_source_name):
    &#34;&#34;&#34;
    Delete Service Broker Content Source

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    content_source_name = Content Source Name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    cs_json = get_sb_content_source_by_name(url,username,password,content_source_name)
    cs_id = cs_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}catalog/api/admin/sources/{1}&#39;.format(api_url_base,cs_id)
    response = requests.delete(api_url, headers=headers, verify=False)
    if response.status_code == 204:
        print(&#39;Successfully Deleted Service Broker Content Source: &#39; + content_source_name)
        return &#39;Successfully Deleted Service Broker Content Source: &#39; + content_source_name
    else:
        print(response.status_code)
        return response.status_code

######Code Stream######
def create_cs_variable(url,username,password,name,proj_name,type,value,description=None):
    &#34;&#34;&#34;
    Creates a Code Stream variable

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    name = Name of the Variable

    proj_name = Name of the project the variable is assocaited

    type = type of vairable to create (REGULAR / RESTRICTED / SECRET)

    value = Value of the variable
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}codestream/api/variables&#39;.format(api_url_base)
    if description == None:
        description = &#34;&#34;
    data =  {
              &#34;description&#34;: description,
              &#34;name&#34;: name,
              &#34;project&#34;: proj_name,
              &#34;type&#34;: type,
              &#34;value&#34;: value
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#39;Successfully Created Code Stream Variable&#39;)
        return &#39;Successfully Created Code Stream Variable&#39;
    else:
        print(response.status_code)
        return response.status_code

def get_variable_by_name(url,username,password,variable_name):
    &#34;&#34;&#34;
    Get Storage Profile by Name and return json information

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    storage_profile_name = Storage Profile Name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}codestream/api/variables&#39;.format(api_url_base)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        var_links = json_data[&#39;links&#39;]
        for x in var_links:
            var_name = json_data[&#39;documents&#39;][x][&#39;name&#39;]
            if var_name == variable_name:
                print(&#34;Found variable: &#34; + variable_name)
                var_id = json_data[&#39;documents&#39;][x][&#39;id&#39;]
                return var_id
            else:
                print(&#34;Variable &#34; + variable_name + &#34; not found!&#34;)
    else:
        print(response.status_code)
        return response.status_code

def delete_variable(url,username,password,variable_name):
    &#34;&#34;&#34;
    Delete Code Stream Variable

    Arguments:
    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    variable_name = Variable Name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    var_id = get_variable_by_name(url,username,password,variable_name)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}codestream/api/variables/{1}&#39;.format(api_url_base,var_id)
    response = requests.delete(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        print(&#39;Successfully Deleted Code Stream Variable: &#39; + variable_name)
        return &#39;Successfully Deleted Code Stream Variable: &#39; + variable_name
    else:
        print(response.status_code)
        return response.status_code

##########Functions Using NON-PUBLIC API Calls##########
def get_nsxt_router_link_by_name(url,username,password,router_name):
    &#34;&#34;&#34;
    Gets the document link to the NSX-T router by name and return the link

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    router_name = Name of the router in NSX-T (i.e. T0-router)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}provisioning/uerp/resources/routers&#39;.format(api_url_base)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        router_links = json_data[&#39;documentLinks&#39;]
        for x in router_links:
            api_url = &#39;{0}provisioning/uerp{1}&#39;.format(api_url_base,x)
            response = requests.get(api_url, headers=headers, verify=False)
            if response.status_code == 200:
                json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
                rtr_name = json_data[&#39;name&#39;]
                if rtr_name == router_name:
                    print(&#34;Found NSXT Router by name: &#34; + router_name)
                    return x
            else:
                print(&#34;Inner Rest call for get_nsxt_router_link_by_name failed with error: &#34; + response.status_code)
                return (&#34;Inner Rest call for get_nsxt_router_link_by_name failed with error: &#34; + response.status_code)
    else:
        print(response.status_code)
        return response.status_code

def create_github_saas_integration(url,username,password,name,private_key):
    &#34;&#34;&#34;
    Creates Github integration in Cloud Assembly

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    name = Name of the Github integration (i.e. ABC Github)

    private_key = Private key created in Github for secure access
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}provisioning/uerp/provisioning/mgmt/endpoints?external=&#39;.format(api_url_base)
    data =  {
                &#34;endpointProperties&#34;: {
                    &#34;url&#34;: &#34;www.github.com&#34;,
                    &#34;privateKey&#34;: private_key
                },
                &#34;customProperties&#34;: {
                    &#34;isExternal&#34;: &#34;true&#34;
                },
                &#34;endpointType&#34;: &#34;com.github.saas&#34;,
                &#34;name&#34;: name
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False, timeout=5)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        print(&#39;Successfully Created GitHub SaaS Integration&#39;)
        return json_data
    else:
        print(response.status_code)
        return response.status_code

def get_integration_by_name(url,username,password,int_name):
    &#34;&#34;&#34;
    Gits a Cloud Assembly Integration by name and returns information via json

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    int_name = Name of the Integration in Cloud Assembly (i.e. ABC Github)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}provisioning/uerp/resources/endpoints&#39;.format(api_url_base)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        endpoint_links = json_data[&#39;documentLinks&#39;]
        for x in endpoint_links:
            api_url = &#39;{0}provisioning/uerp{1}&#39;.format(api_url_base,x)
            response = requests.get(api_url, headers=headers, verify=False)
            if response.status_code == 200:
                json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
                integration_name = json_data[&#39;name&#39;]
                if integration_name == int_name:
                    print(&#34;Found Integration by name: &#34; + int_name)
                    int_id = x[21:]
                    return int_id
            else:
                print(&#34;Inner Rest call for get_nsxt_router_link_by_name failed with error: &#34; + response.status_code)
                return (&#34;Inner Rest call for get_nsxt_router_link_by_name failed with error: &#34; + response.status_code)
    else:
        print(response.status_code)
        return response.status_code

def create_ansible_oss_integration(url,username,password,name,private_key,private_id,hostname,inventory_path,use_sudo=&#34;true&#34;,ssh_port=&#34;22&#34;):
    &#34;&#34;&#34;
    Creates an Ansible Open Source integration in Cloud Assembly

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    name = Name of the Ansible OSS integration

    private_key = Password used for integration

    private_id = Username used for integration

    hostname = FQDN or IP of Ansible Server

    inventory_path = Path to inventory file on ansible server

    use_sudo = Use sudo when running commands (default is true)

    ssh_port = Port Ansible will use to run commands on machines (default is port 22)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}provisioning/uerp/provisioning/mgmt/endpoints?external&#39;.format(api_url_base)
    data =  {
              &#34;endpointProperties&#34;: {
                &#34;hostName&#34;: hostname,
                &#34;dcId&#34;: &#34;onprem&#34;,
                &#34;inventoryFilePath&#34;: inventory_path,
                &#34;privateKeyId&#34;: private_id,
                &#34;privateKey&#34;: private_key,
                &#34;useSudo&#34;: use_sudo,
                &#34;location&#34;: &#34;Private&#34;,
                &#34;sshPort&#34;: ssh_port,
                &#34;acceptSelfSignedCertificate&#34;: &#34;true&#34;
              },
              &#34;customProperties&#34;: {
                &#34;isExternal&#34;: &#34;true&#34;
              },
              &#34;endpointType&#34;: &#34;ansible&#34;,
              &#34;associatedEndpointLinks&#34;: [],
              &#34;name&#34;: name,
              &#34;tagLinks&#34;: []
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#39;Successfully Created Ansible OSS Integration&#39;)
    else:
        print(response.status_code)
        return response.status_code

def create_ansibletower_integration(url,username,password,name,private_key,private_id,hostname,use_sudo=&#34;true&#34;,ssh_port=&#34;22&#34;):
    &#34;&#34;&#34;
    Creates an Ansible Open Source integration in Cloud Assembly

    create_ansibletower_integration(url,username,password,name,private_key,private_id,hostname)

    Arguments:
    url = vRA FQDN
    username = vRA Admin user
    password = vRA Admin password
    name = Name of the Ansible OSS integration
    private_key = Password used for integration
    private_id = Username used for integration
    hostname = FQDN or IP of Ansible Server
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}provisioning/uerp/provisioning/mgmt/endpoints?external&#39;.format(api_url_base)
    data =  {
              &#34;endpointProperties&#34;: {
                &#34;hostName&#34;: hostname,
                &#34;dcId&#34;: &#34;onprem&#34;,
                &#34;privateKeyId&#34;: private_id,
                &#34;privateKey&#34;: private_key,
                &#34;location&#34;: &#34;Private&#34;,
                &#34;acceptSelfSignedCertificate&#34;: &#34;true&#34;
              },
              &#34;customProperties&#34;: {
                &#34;isExternal&#34;: &#34;true&#34;
              },
              &#34;endpointType&#34;: &#34;ansible.tower&#34;,
              &#34;associatedEndpointLinks&#34;: [],
              &#34;name&#34;: name,
              &#34;tagLinks&#34;: []
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#39;Successfully Created Ansible Tower Integration&#39;)
    else:
        print(response.status_code)
        return response.status_code

def delete_integration_by_name(url,username,password,int_name):
    &#34;&#34;&#34;
    Delete Integration in vRA Cloud Assembly

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    int_name = Integration Name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    int_id = get_integration_by_name(url,username,password,int_name)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}provisioning/uerp/resources/endpoints/{1}&#39;.format(api_url_base,cs_id)
    response = requests.delete(api_url, headers=headers, verify=False)
    if response.status_code == 204:
        print(&#39;Successfully Deleted Integration in Cloud Assembly: &#39; + content_source_name)
        return &#39;Successfully Deleted Integration in Cloud Assembly: &#39; + content_source_name
    else:
        print(response.status_code)
        return response.status_code

#url = &#34;vra8-dev-ga.cmbu.local&#34;
#username = &#34;configuser&#34;
#password = &#34;VMware1!&#34;</code></pre>
</details>
</section>
<section>
</section>
<section>
</section>
<section>
<h2 class="section-title" id="header-functions">Functions</h2>
<dl>
<dt id="vra_module.add_admin_to_project"><code class="name flex">
<span>def <span class="ident">add_admin_to_project</span></span>(<span>url, username, password, projname, admin_email)</span>
</code></dt>
<dd>
<div class="desc"><p>Add and admin to the Project</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA Admin user</p>
<p>password = vRA Admin password</p>
<p>projname = Provide name of project you want to add Admin to</p>
<p>admin_email: Email of the admin you want to add (admins can manage a project)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def add_admin_to_project(url,username,password,projname,admin_email):
    &#34;&#34;&#34;
    Add and admin to the Project

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    projname = Provide name of project you want to add Admin to

    admin_email: Email of the admin you want to add (admins can manage a project)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username,password)
    proj_json = get_proj_by_name(url,username,password,projname)
    proj_id = proj_json[&#39;id&#39;]
    proj_admins = proj_json[&#39;administrators&#39;]
    admin_len = (len(proj_admins))
    new_admin = {&#34;email&#34;: admin_email,&#34;type&#34;: &#34;user&#34;}
    payload = []
    if admin_len == 0:
        payload.append(new_admin)
    else:
        n = 0
        end = admin_len - 1
        while True:
            if n &lt;= end:
                payload.append(proj_admins[n])
                n = n + 1
            elif n &gt; end:
                break
        payload.append(new_admin)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/projects/{1}&#39;.format(api_url_base,proj_id)
    data =  {
              &#34;administrators&#34;: payload
            }
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#34;Successfully added &#34; + admin_email + &#34; to Project as admin&#34;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.add_cloudzone_to_project"><code class="name flex">
<span>def <span class="ident">add_cloudzone_to_project</span></span>(<span>url, username, password, projname, czname, priority=None, store_limit=None, cpu_limit=None, mem_limit=None, max_num=None)</span>
</code></dt>
<dd>
<div class="desc"><p>Add CloudZone to a Project, once the CloudZone is added that Project can then consume resources in that CloudZone
via Cloud Templates and Code Stream Pipelines.</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>projname = Provide name of a project you want to add the CloudZone</p>
<p>czname = Name of CloudZone to Add (e.g. - "AWS-Cloud-Account / us-west-1")</p>
<p>priority = 0 is the highest</p>
<p>store_limit = Max amount of storage that the cloud zone can consume in this project(default=0, vSphere Cloud Zone only)</p>
<p>cpu_limit = Max number of virtual CPUs that the cloud zone can consume in this project(default=0, unlimited)</p>
<p>mem_limit = Maximum amount of memory (MB) that the cloud zone can consume in this project(default=0, unlimited)</p>
<p>max_num = Maximum amount of instances that the cloud zone can deploy in this project(default=0, unlimited)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def add_cloudzone_to_project(url,username,password,projname,czname,priority=None,store_limit=None,cpu_limit=None,mem_limit=None,max_num=None):
    &#34;&#34;&#34;
    Add CloudZone to a Project, once the CloudZone is added that Project can then consume resources in that CloudZone
    via Cloud Templates and Code Stream Pipelines.

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    projname = Provide name of a project you want to add the CloudZone

    czname = Name of CloudZone to Add (e.g. - &#34;AWS-Cloud-Account / us-west-1&#34;)

    priority = 0 is the highest

    store_limit = Max amount of storage that the cloud zone can consume in this project(default=0, vSphere Cloud Zone only)

    cpu_limit = Max number of virtual CPUs that the cloud zone can consume in this project(default=0, unlimited)

    mem_limit = Maximum amount of memory (MB) that the cloud zone can consume in this project(default=0, unlimited)

    max_num = Maximum amount of instances that the cloud zone can deploy in this project(default=0, unlimited)

    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username,password)
    proj_json = get_proj_by_name(url,username,password,projname)
    proj_id = proj_json[&#39;id&#39;]
    proj_zones = proj_json[&#39;zones&#39;]
    zone_len = (len(proj_zones))
    czid = get_czid_by_name(url,username,password,czname)
    if priority is None:
        priority = 0
    if store_limit is None:
        store_limit = 0
    if cpu_limit is None:
        cpu_limit = 0
    if mem_limit is None:
        mem_limit = 0
    if max_num is None:
        max_num = 0
    new_zone = {&#34;storageLimitGB&#34;: store_limit,&#34;cpuLimit&#34;: cpu_limit,&#34;memoryLimitMB&#34;: mem_limit,&#34;zoneId&#34;: czid,&#34;maxNumberInstances&#34;: max_num,&#34;priority&#34;: priority}
    payload = []
    if zone_len == 0:
        payload.append(new_zone)
    else:
        n = 0
        end = zone_len - 1
        while True:
            if n &lt;= end:
                payload.append(proj_zones[n])
                n = n + 1
            elif n &gt; end:
                break
        payload.append(new_zone)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/projects/{1}&#39;.format(api_url_base,proj_id)
    data =  {
              &#34;zoneAssignmentConfigurations&#34;: payload
            }
    print(data)
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#34;Successfully added Cloud Zone &#34; + czname + &#34; to Project&#34;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.add_group_admin_to_project"><code class="name flex">
<span>def <span class="ident">add_group_admin_to_project</span></span>(<span>url, username, password, projname, group_email)</span>
</code></dt>
<dd>
<div class="desc"><p>Add group admin to a Project</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA Admin user</p>
<p>password = vRA Admin password</p>
<p>projname = Provide name of project to add the admin group</p>
<p>group_email: Email of the group you want to add (i.e. - vRA-All-Services-admins@acme.local</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def add_group_admin_to_project(url,username,password,projname,group_email):
    &#34;&#34;&#34;
    Add group admin to a Project

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    projname = Provide name of project to add the admin group

    group_email: Email of the group you want to add (i.e. - vRA-All-Services-admins@acme.local

    &#34;&#34;&#34;


    api_url_base = set_bas_url(url)
    access_key = get_token(url,username,password)
    proj_json = get_proj_by_name(url,username,password,projname)
    proj_id = proj_json[&#39;id&#39;]
    proj_admins = proj_json[&#39;administrators&#39;]
    admin_len = (len(proj_admins))
    new_admin = {&#34;email&#34;: group_email,&#34;type&#34;: &#34;group&#34;}
    payload = []
    if admin_len == 0:
        payload.append(new_admin)
    else:
        n = 0
        end = admin_len - 1
        while True:
            if n &lt;= end:
                payload.append(proj_admins[n])
                n = n + 1
            elif n &gt; end:
                break
        payload.append(new_admin)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/projects/{1}&#39;.format(api_url_base,proj_id)
    data =  {
              &#34;administrators&#34;: payload
            }
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#34;Successfully added &#34; + group_email + &#34; to Project as admin&#34;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.add_group_member_to_project"><code class="name flex">
<span>def <span class="ident">add_group_member_to_project</span></span>(<span>url, username, password, projname, group_email)</span>
</code></dt>
<dd>
<div class="desc"><p>Add a group to a Project</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA Admin user</p>
<p>password = vRA Admin password</p>
<p>projname = Provide name of project you want to add group members to</p>
<p>group_email = Email of the group you want to add (e.g. - vRA-All-Services-Users@acme.local)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def add_group_member_to_project(url,username,password,projname,group_email):
    &#34;&#34;&#34;
    Add a group to a Project

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    projname = Provide name of project you want to add group members to

    group_email = Email of the group you want to add (e.g. - vRA-All-Services-Users@acme.local)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    proj_json = get_proj_by_name(url,username,password,projname)
    proj_id = proj_json[&#39;id&#39;]
    proj_members = proj_json[&#39;members&#39;]
    member_len = (len(proj_members))
    new_member = {&#34;email&#34;: group_email,&#34;type&#34;: &#34;group&#34;}
    payload = []
    if member_len == 0:
        payload.append(new_member)
    else:
        n = 0
        end = member_len - 1
        while True:
            if n &lt;= end:
                payload.append(proj_members[n])
                n = n + 1
            elif n &gt; end:
                break
        payload.append(new_member)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/projects/{1}&#39;.format(api_url_base,proj_id)
    data =  {
              &#34;members&#34;: payload
            }
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#34;Successfully added &#34; + group_email + &#34; to Project as member&#34;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.add_member_to_project"><code class="name flex">
<span>def <span class="ident">add_member_to_project</span></span>(<span>url, username, password, projname, member_email)</span>
</code></dt>
<dd>
<div class="desc"><p>Add a member to a Project</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA Admin user</p>
<p>password = vRA Admin password</p>
<p>projname = Project you want to add the user to</p>
<p>member_email = email of the user you want to add to the project</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def add_member_to_project(url,username,password,projname,member_email):
    &#34;&#34;&#34;
    Add a member to a Project

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    projname = Project you want to add the user to

    member_email = email of the user you want to add to the project
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    proj_json = get_proj_by_name(url,username,password,projname)
    proj_id = proj_json[&#39;id&#39;]
    proj_members = proj_json[&#39;members&#39;]
    member_len = (len(proj_members))
    new_member = {&#34;email&#34;: member_email,&#34;type&#34;: &#34;user&#34;}
    payload = []
    if member_len == 0:
        payload.append(new_member)
    else:
        n = 0
        end = member_len - 1
        while True:
            if n &lt;= end:
                payload.append(proj_members[n])
                n = n + 1
            elif n &gt; end:
                break
        payload.append(new_member)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/projects/{1}&#39;.format(api_url_base,proj_id)
    data =  {
              &#34;members&#34;: payload
            }
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#34;Successfully added &#34; + member_email + &#34; to Project as member&#34;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.add_network_to_profile"><code class="name flex">
<span>def <span class="ident">add_network_to_profile</span></span>(<span>url, username, password, region_name, net_profile_name, fabric_net_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Adds a discovered network to an existing Network Profile</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>net_profile_name = The name of the network profile (i.e.vsphere-networks)</p>
<p>region_name = The datacenter id for the Cloud Account (i.e. Datacenter:datacenter-2 or eastus or us-west-1)</p>
<p>fabric_net_name = The name of the network that was discovered by vRA discover service (i.e.web-network)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def add_network_to_profile(url,username,password,region_name,net_profile_name,fabric_net_name):
    &#34;&#34;&#34;
    Adds a discovered network to an existing Network Profile

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    net_profile_name = The name of the network profile (i.e.vsphere-networks)

    region_name = The datacenter id for the Cloud Account (i.e. Datacenter:datacenter-2 or eastus or us-west-1)

    fabric_net_name = The name of the network that was discovered by vRA discover service (i.e.web-network)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    reg_id = get_cloud_regionid_by_name(url,username,password,region_name)
    prof_json = get_netprofile_by_name(url,username,password,net_profile_name)
    fab_net_json = get_fabric_network_by_name(url,username,password,fabric_net_name)
    fab_net_id = fab_net_json[&#39;id&#39;]
    fab_id = []
    fab_id.append(fab_net_id)
    try:
        current_assigned_networks = prof_json[&#39;_links&#39;][&#39;fabric-networks&#39;][&#39;hrefs&#39;]
        for net in current_assigned_networks:
            net = net[26:]
            fab_id.append(net)
    except:
        print(&#34;Currently no networks assigned&#34;)
    prof_id = prof_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/network-profiles/{1}&#39;.format(api_url_base,prof_id)
    data = {
              &#34;fabricNetworkIds&#34;: fab_id
            }
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        print(&#39;Successfully Added Network to Network Profile: &#39; + net_profile_name)
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.add_nsxt_network_to_profile"><code class="name flex">
<span>def <span class="ident">add_nsxt_network_to_profile</span></span>(<span>url, username, password, region_name, net_profile_name, fabric_net_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Adds a discovered NSX-T network to an existing Network Profile</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>net_profile_name = The name of the network profile (i.e.vsphere-networks)</p>
<p>region_name = The datacenter id for the Cloud Account (i.e. Datacenter:datacenter-2 or eastus or us-west-1)</p>
<p>fabric_net_name = The name of the network that was discovered by vRA discover service (i.e.web-network)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def add_nsxt_network_to_profile(url,username,password,region_name,net_profile_name,fabric_net_name):
    &#34;&#34;&#34;
    Adds a discovered NSX-T network to an existing Network Profile

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    net_profile_name = The name of the network profile (i.e.vsphere-networks)

    region_name = The datacenter id for the Cloud Account (i.e. Datacenter:datacenter-2 or eastus or us-west-1)

    fabric_net_name = The name of the network that was discovered by vRA discover service (i.e.web-network)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    reg_id = get_cloud_regionid_by_name(url,username,password,region_name)
    prof_json = get_netprofile_by_name(url,username,password,net_profile_name)
    fab_net_json = get_nsxt_fabric_network_by_name(url,username,password,fabric_net_name)
    fab_net_id = fab_net_json[&#39;id&#39;]
    fab_id = []
    fab_id.append(fab_net_id)
    try:
        current_assigned_networks = prof_json[&#39;_links&#39;][&#39;fabric-networks&#39;][&#39;hrefs&#39;]
        for net in current_assigned_networks:
            net = net[26:]
            fab_id.append(net)
    except:
        print(&#34;Currently no networks assigned&#34;)
    prof_id = prof_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/network-profiles/{1}&#39;.format(api_url_base,prof_id)
    data = {
              &#34;fabricNetworkIds&#34;: fab_id
            }
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        print(&#39;Successfully Added NSXT Network to Network Profile: &#39; + net_profile_name)
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.add_sec_group_vsphere_net_profile"><code class="name flex">
<span>def <span class="ident">add_sec_group_vsphere_net_profile</span></span>(<span>url, username, password, net_profile_name, secgroup_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Adds discovered security group to a network profile.</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>net_profile_name = The name of the network profile (i.e.vsphere-networks)</p>
<p>secgroup_name = The name of the existing security group (i.e.web-security)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def add_sec_group_vsphere_net_profile(url,username,password,net_profile_name,secgroup_name):
    &#34;&#34;&#34;
    Adds discovered security group to a network profile.

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    net_profile_name = The name of the network profile (i.e.vsphere-networks)

    secgroup_name = The name of the existing security group (i.e.web-security)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    net_prof_json = get_netprofile_by_name(url,username,password,net_profile_name)
    net_prof_id = net_prof_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/network-profiles/{1}&#39;.format(api_url_base,net_prof_id)
    try:
        current_secgroups = net_prof_json[&#39;_links&#39;][&#39;security-groups&#39;][&#39;hrefs&#39;]
        sec_groups = []
        for x in current_secgroups:
            x = x[26:]
            sec_groups.append(x)
        new_sec_group = get_sec_group_by_name(url,username,password,secgroup_name)
        sec_groups.append(new_sec_group)
    except:
        print(&#34;Currently no Security Groups assigned&#34;)
        sec_groups = []
        new_sec_group = get_sec_group_by_name(url,username,password,secgroup_name)
        sec_groups.append(new_sec_group)
    data = {
              &#34;securityGroupIds&#34;: sec_groups
            }
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        print(&#39;Successfully Added Security Group: &#39; + secgroup_name)
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.config_ondemand_sec_groups_vsphere_network_profile"><code class="name flex">
<span>def <span class="ident">config_ondemand_sec_groups_vsphere_network_profile</span></span>(<span>url, username, password, net_profile_name, edge_router_name, t0_router_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Configues vSphere network profile for on-demand security groups</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>net_profile_name = The name of the network profile (i.e.vsphere-networks)</p>
<p>edge_router_name = Name of the edge router in NSX-T</p>
<p>t0_router_name = Name of the T0 router in NSX-T</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def config_ondemand_sec_groups_vsphere_network_profile(url,username,password,net_profile_name,edge_router_name,t0_router_name):
    &#34;&#34;&#34;
    Configues vSphere network profile for on-demand security groups

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    net_profile_name = The name of the network profile (i.e.vsphere-networks)

    edge_router_name = Name of the edge router in NSX-T

    t0_router_name = Name of the T0 router in NSX-T
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    net_prof_json = get_netprofile_by_name(url,username,password,net_profile_name)
    net_prof_id = net_prof_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/network-profiles/{1}&#39;.format(api_url_base,net_prof_id)
    current_dc_id = net_prof_json[&#39;customProperties&#39;][&#39;datacenterId&#39;]
    edge_router_link = get_nsxt_router_link_by_name(url,username,password,edge_router_name)
    t0_router_link = get_nsxt_router_link_by_name(url,username,password,t0_router_name)
    data = {
            &#34;isolationType&#34;: &#34;SECURITY_GROUP&#34;,
            &#34;customProperties&#34;: {
                &#34;datacenterId&#34;: current_dc_id,
                &#34;edgeClusterRouterStateLink&#34;: edge_router_link,
                &#34;tier0LogicalRouterStateLink&#34;: t0_router_link
            }
           }
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        print(&#39;Successfully Configured On-Demand Security Group: &#39; + net_profile_name)
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.create_actions_content_source"><code class="name flex">
<span>def <span class="ident">create_actions_content_source</span></span>(<span>url, username, password, name, int_name, proj_name, repo, branch, path)</span>
</code></dt>
<dd>
<div class="desc"><p>Creates an action content source on a github integration</p>
<h2 id="arguments">Arguments</h2>
<p>url = vRA FQDN</p>
<p>username = vRA Admin user</p>
<p>password = vRA Admin password</p>
<p>name = Name of the content source (i.e. ABC Actions)</p>
<p>int_name = Name of the integration (i.e. ABC GitHub Integration)</p>
<p>proj_name = Name of vRA Project to associate content source</p>
<p>repo = Name of the github repository</p>
<p>branch = Name of branch in repo (i.e. master)</p>
<p>path = path to folder of actions (i.e actions)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def create_actions_content_source(url,username,password,name,int_name,proj_name,repo,branch,path):
    &#34;&#34;&#34;
    Creates an action content source on a github integration

    Arguments:


    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    name = Name of the content source (i.e. ABC Actions)

    int_name = Name of the integration (i.e. ABC GitHub Integration)

    proj_name = Name of vRA Project to associate content source

    repo = Name of the github repository

    branch = Name of branch in repo (i.e. master)

    path = path to folder of actions (i.e actions)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    proj_json = get_proj_by_name(url,username,password,proj_name)
    proj_id = proj_json[&#39;id&#39;]
    int_id = get_integration_by_name(url,username,password,int_name)
    api_url = &#39;{0}content/api/sources&#39;.format(api_url_base)
    data =  {
              &#34;name&#34;: name,
              &#34;typeId&#34;: &#34;com.github&#34;,
              &#34;syncEnabled&#34; : &#34;true&#34;,
              &#34;projectId&#34; : proj_id,
              &#34;config&#34;: {
                &#34;integrationId&#34; : int_id,
                &#34;repository&#34; : &#34;mcclanc/vra8-content&#34;,
                &#34;path&#34; : path,
                &#34;branch&#34; : &#34;master&#34;,
                &#34;contentType&#34; : &#34;abx_scripts&#34;
              }
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        print(&#39;Successfully Created Actions Content Source&#39;)
        return &#39;Successfully Created Actions Content Source&#39;
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.create_ansible_oss_integration"><code class="name flex">
<span>def <span class="ident">create_ansible_oss_integration</span></span>(<span>url, username, password, name, private_key, private_id, hostname, inventory_path, use_sudo='true', ssh_port='22')</span>
</code></dt>
<dd>
<div class="desc"><p>Creates an Ansible Open Source integration in Cloud Assembly</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA Admin user</p>
<p>password = vRA Admin password</p>
<p>name = Name of the Ansible OSS integration</p>
<p>private_key = Password used for integration</p>
<p>private_id = Username used for integration</p>
<p>hostname = FQDN or IP of Ansible Server</p>
<p>inventory_path = Path to inventory file on ansible server</p>
<p>use_sudo = Use sudo when running commands (default is true)</p>
<p>ssh_port = Port Ansible will use to run commands on machines (default is port 22)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def create_ansible_oss_integration(url,username,password,name,private_key,private_id,hostname,inventory_path,use_sudo=&#34;true&#34;,ssh_port=&#34;22&#34;):
    &#34;&#34;&#34;
    Creates an Ansible Open Source integration in Cloud Assembly

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    name = Name of the Ansible OSS integration

    private_key = Password used for integration

    private_id = Username used for integration

    hostname = FQDN or IP of Ansible Server

    inventory_path = Path to inventory file on ansible server

    use_sudo = Use sudo when running commands (default is true)

    ssh_port = Port Ansible will use to run commands on machines (default is port 22)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}provisioning/uerp/provisioning/mgmt/endpoints?external&#39;.format(api_url_base)
    data =  {
              &#34;endpointProperties&#34;: {
                &#34;hostName&#34;: hostname,
                &#34;dcId&#34;: &#34;onprem&#34;,
                &#34;inventoryFilePath&#34;: inventory_path,
                &#34;privateKeyId&#34;: private_id,
                &#34;privateKey&#34;: private_key,
                &#34;useSudo&#34;: use_sudo,
                &#34;location&#34;: &#34;Private&#34;,
                &#34;sshPort&#34;: ssh_port,
                &#34;acceptSelfSignedCertificate&#34;: &#34;true&#34;
              },
              &#34;customProperties&#34;: {
                &#34;isExternal&#34;: &#34;true&#34;
              },
              &#34;endpointType&#34;: &#34;ansible&#34;,
              &#34;associatedEndpointLinks&#34;: [],
              &#34;name&#34;: name,
              &#34;tagLinks&#34;: []
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#39;Successfully Created Ansible OSS Integration&#39;)
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.create_ansibletower_integration"><code class="name flex">
<span>def <span class="ident">create_ansibletower_integration</span></span>(<span>url, username, password, name, private_key, private_id, hostname, use_sudo='true', ssh_port='22')</span>
</code></dt>
<dd>
<div class="desc"><p>Creates an Ansible Open Source integration in Cloud Assembly</p>
<p>create_ansibletower_integration(url,username,password,name,private_key,private_id,hostname)</p>
<p>Arguments:
url = vRA FQDN
username = vRA Admin user
password = vRA Admin password
name = Name of the Ansible OSS integration
private_key = Password used for integration
private_id = Username used for integration
hostname = FQDN or IP of Ansible Server</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def create_ansibletower_integration(url,username,password,name,private_key,private_id,hostname,use_sudo=&#34;true&#34;,ssh_port=&#34;22&#34;):
    &#34;&#34;&#34;
    Creates an Ansible Open Source integration in Cloud Assembly

    create_ansibletower_integration(url,username,password,name,private_key,private_id,hostname)

    Arguments:
    url = vRA FQDN
    username = vRA Admin user
    password = vRA Admin password
    name = Name of the Ansible OSS integration
    private_key = Password used for integration
    private_id = Username used for integration
    hostname = FQDN or IP of Ansible Server
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}provisioning/uerp/provisioning/mgmt/endpoints?external&#39;.format(api_url_base)
    data =  {
              &#34;endpointProperties&#34;: {
                &#34;hostName&#34;: hostname,
                &#34;dcId&#34;: &#34;onprem&#34;,
                &#34;privateKeyId&#34;: private_id,
                &#34;privateKey&#34;: private_key,
                &#34;location&#34;: &#34;Private&#34;,
                &#34;acceptSelfSignedCertificate&#34;: &#34;true&#34;
              },
              &#34;customProperties&#34;: {
                &#34;isExternal&#34;: &#34;true&#34;
              },
              &#34;endpointType&#34;: &#34;ansible.tower&#34;,
              &#34;associatedEndpointLinks&#34;: [],
              &#34;name&#34;: name,
              &#34;tagLinks&#34;: []
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#39;Successfully Created Ansible Tower Integration&#39;)
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.create_aws_ca"><code class="name flex">
<span>def <span class="ident">create_aws_ca</span></span>(<span>url, username, password, aws_key_id, aws_access_key, name)</span>
</code></dt>
<dd>
<div class="desc"><p>Setup and configure AWS Cloud Accounts</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>aws_key_id = AWS Key</p>
<p>aws_access_key = AWS Access Key</p>
<p>name = name of AWS Integration</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def create_aws_ca(url,username,password,aws_key_id,aws_access_key,name):
    &#34;&#34;&#34;
    Setup and configure AWS Cloud Accounts

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    aws_key_id = AWS Key

    aws_access_key = AWS Access Key

    name = name of AWS Integration

    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/cloud-accounts-aws&#39;.format(api_url_base)
    data =  {
                &#34;description&#34;: &#34;AWS Cloud Account&#34;,
                &#34;accessKeyId&#34;: aws_key_id,
                &#34;secretAccessKey&#34;: aws_access_key,
                &#34;cloudAccountProperties&#34;: {

                },
                &#34;regionIds&#34;: [
                    &#34;us-west-1&#34;
                ],
                &#34;createDefaultZones&#34; : &#34;true&#34;,
                &#34;name&#34;: name
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        print(&#39;Successfully Created AWS Cloud Account&#39;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.create_aws_storage_profile"><code class="name flex">
<span>def <span class="ident">create_aws_storage_profile</span></span>(<span>url, username, password, name, region_name, encrypted='false', devicetype='ebs', volumetype='standard', tag_key=None, iops_limit=None, tag_value=None, default='false')</span>
</code></dt>
<dd>
<div class="desc"><p>Creates a AWS Storage Profile</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA Admin user</p>
<p>password = vRA Admin password</p>
<p>name = Name of the Storage Profile</p>
<p>region_name = Name of the region this profile is attached (i.e us-west-1)</p>
<p>encrypted = Is datastore encrypted (true or false(default))</p>
<p>devicetype = The type of storage device to use (ebs / instance-store)</p>
<p>volumetype = The type of volume (gp2 / io1 / sc1 / st1 / standard)</p>
<p>tag_key = The key for the tag (i.e env:tag_value)</p>
<p>tag_value = Th value for the tag (i.e. tag_key:aws)</p>
<p>iops_limit = Sets the IOPs limit for the Storage profile (if not set value is set to unlimited)</p>
<p>default = Is this the default profile for the region (true / false (default))</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def create_aws_storage_profile(url,username,password,name,region_name,encrypted=&#34;false&#34;,devicetype=&#34;ebs&#34;,volumetype=&#34;standard&#34;,tag_key=None,iops_limit=None,tag_value=None,default=&#34;false&#34;):
    &#34;&#34;&#34;
    Creates a AWS Storage Profile

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    name = Name of the Storage Profile

    region_name = Name of the region this profile is attached (i.e us-west-1)

    encrypted = Is datastore encrypted (true or false(default))

    devicetype = The type of storage device to use (ebs / instance-store)

    volumetype = The type of volume (gp2 / io1 / sc1 / st1 / standard)

    tag_key = The key for the tag (i.e env:tag_value)

    tag_value = Th value for the tag (i.e. tag_key:aws)

    iops_limit = Sets the IOPs limit for the Storage profile (if not set value is set to unlimited)

    default = Is this the default profile for the region (true / false (default))
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    reg_id = get_cloud_regionid_by_name(url,username,password,region_name)
    if tag_key != None:
        if tag_value != None:
            tag_prep = {&#34;key&#34;: tag_key,&#34;value&#34;: tag_value}
            tag = []
            tag.append(tag_prep)
    else:
        tag = []
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/storage-profiles-aws&#39;.format(api_url_base)
    payload = {
                  &#34;deviceType&#34;: devicetype,
                  &#34;volumeType&#34;: volumetype,
                  &#34;supportsEncryption&#34;: encrypted,
                  &#34;regionId&#34;: reg_id,
                  &#34;name&#34;: name,
                  &#34;description&#34;: &#34;AWS Storage Profile&#34;,
                  &#34;defaultItem&#34;: default,
                  &#34;tags&#34;: tag
                }
    if iops_limit != None:
        c = json.dumps(payload)
        c = c[1:-1]
        iops = {&#34;limitIops&#34;: iops_limit}
        d = json.dumps(iops)
        d = d[1:-1]
        combined = c + &#34;,&#34; + d
        payload = &#34;{&#34; + combined + &#34;}&#34;
        payload = json.loads(payload)
    data = payload
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        print(&#39;Successfully Created AWS Storage Profile&#39;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.create_azure_ca"><code class="name flex">
<span>def <span class="ident">create_azure_ca</span></span>(<span>url, username, password, sub_id, ten_id, app_id, app_key, name, region_id)</span>
</code></dt>
<dd>
<div class="desc"><p>Setup and Create Azure Cloud Account</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>sub_id = Azure Subscription ID</p>
<p>ten_id = Azure Tenant ID</p>
<p>app_id = Azure Client Application ID</p>
<p>app_key = Azure Client Application Secret Key</p>
<p>region_id = Azure Region (example: eastus)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def create_azure_ca(url,username,password,sub_id,ten_id,app_id,app_key,name,region_id):
    &#34;&#34;&#34;
    Setup and Create Azure Cloud Account

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    sub_id = Azure Subscription ID

    ten_id = Azure Tenant ID

    app_id = Azure Client Application ID

    app_key = Azure Client Application Secret Key

    region_id = Azure Region (example: eastus)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/cloud-accounts-azure&#39;.format(api_url_base)
    data =  {
              &#34;name&#34;: name,
              &#34;description&#34;: &#34;Azure Cloud Account&#34;,
              &#34;subscriptionId&#34;: sub_id,
              &#34;tenantId&#34;: ten_id,
              &#34;clientApplicationId&#34;: app_id,
              &#34;clientApplicationSecretKey&#34;: app_key,
              &#34;regionIds&#34;: [
                  region_id
               ],
              &#34;createDefaultZones&#34;: &#34;true&#34;
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        print(&#39;Successfully Created Azure Cloud Account&#39;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.create_azure_storage_profile"><code class="name flex">
<span>def <span class="ident">create_azure_storage_profile</span></span>(<span>url, username, password, name, region_name, encrypted='false', disktype='Standard_LRS', diskcaching='None', oscaching='None', tag_key=None, tag_value=None, default='false')</span>
</code></dt>
<dd>
<div class="desc"><p>Creates a Azure Storage Profile</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA Admin user</p>
<p>password = vRA Admin password</p>
<p>name = Name of the Storage Profile</p>
<p>region_name = Name of the region this profile is attached (i.e us-west-1)</p>
<p>encrypted = Is datastore encrypted (true or false(default))</p>
<p>disktype = The type of storage device to use (Standard_LRS / Premium_LRS)</p>
<p>diskcaching = Cache the data disk? (None / ReadOnly / ReadWrite)</p>
<p>oscaching = Cache the OS disk? (None / ReadOnly / ReadWrite)</p>
<p>tag_key = The key for the tag (i.e env:tag_value)</p>
<p>tag_value = Th value for the tag (i.e. tag_key:azure)</p>
<p>default = Is this the default profile for the region (true / false (default))</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def create_azure_storage_profile(url,username,password,name,region_name,encrypted=&#34;false&#34;,disktype=&#34;Standard_LRS&#34;,diskcaching=&#34;None&#34;,oscaching=&#34;None&#34;,tag_key=None,tag_value=None,default=&#34;false&#34;):
    &#34;&#34;&#34;
    Creates a Azure Storage Profile

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    name = Name of the Storage Profile

    region_name = Name of the region this profile is attached (i.e us-west-1)

    encrypted = Is datastore encrypted (true or false(default))

    disktype = The type of storage device to use (Standard_LRS / Premium_LRS)

    diskcaching = Cache the data disk? (None / ReadOnly / ReadWrite)

    oscaching = Cache the OS disk? (None / ReadOnly / ReadWrite)

    tag_key = The key for the tag (i.e env:tag_value)

    tag_value = Th value for the tag (i.e. tag_key:azure)

    default = Is this the default profile for the region (true / false (default))
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    reg_id = get_cloud_regionid_by_name(url,username,password,region_name)
    if tag_key != None:
        if tag_value != None:
            tag_prep = {&#34;key&#34;: tag_key,&#34;value&#34;: tag_value}
            tag = []
            tag.append(tag_prep)
    else:
        tag = []
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/storage-profiles-azure&#39;.format(api_url_base)
    data = {
             &#34;supportsEncryption&#34;: encrypted,
             &#34;regionId&#34;: reg_id,
             &#34;name&#34;: name,
             &#34;description&#34;: &#34;Azure Storage Profile&#34;,
             &#34;defaultItem&#34;: default,
             &#34;diskType&#34;: disktype,
             &#34;dataDiskCaching&#34;: diskcaching,
             &#34;osDiskCaching&#34;: oscaching,
             &#34;tags&#34;: tag
           }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        print(&#39;Successfully Created Azure Storage Profile&#39;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.create_blueprint_content_source"><code class="name flex">
<span>def <span class="ident">create_blueprint_content_source</span></span>(<span>url, username, password, name, int_name, proj_name, repo, branch, path)</span>
</code></dt>
<dd>
<div class="desc"><p>Creates a cloud template content source on a github integration</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA Admin user</p>
<p>password = vRA Admin password</p>
<p>name = Name of the content source (i.e. ABC Actions)</p>
<p>int_name = Name of the integration (i.e. ABC GitHub Integration)</p>
<p>proj_name = Name of vRA Project to associate content source</p>
<p>repo = Name of the github repository</p>
<p>branch = Name of branch in repo (i.e. master)</p>
<p>path = Folder name storing cloud templates in repo (i.e templates)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def create_blueprint_content_source(url,username,password,name,int_name,proj_name,repo,branch,path):
    &#34;&#34;&#34;
    Creates a cloud template content source on a github integration

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    name = Name of the content source (i.e. ABC Actions)

    int_name = Name of the integration (i.e. ABC GitHub Integration)

    proj_name = Name of vRA Project to associate content source

    repo = Name of the github repository

    branch = Name of branch in repo (i.e. master)

    path = Folder name storing cloud templates in repo (i.e templates)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    proj_json = get_proj_by_name(url,username,password,proj_name)
    proj_id = proj_json[&#39;id&#39;]
    int_id = get_integration_by_name(url,username,password,int_name)
    api_url = &#39;{0}content/api/sources&#39;.format(api_url_base)
    data =  {
              &#34;name&#34;: name,
              &#34;typeId&#34;: &#34;com.github&#34;,
              &#34;syncEnabled&#34; : &#34;true&#34;,
              &#34;projectId&#34; : proj_id,
              &#34;config&#34;: {
                &#34;integrationId&#34; : int_id,
                &#34;repository&#34; : &#34;mcclanc/vra8-content&#34;,
                &#34;path&#34; : path,
                &#34;branch&#34; : &#34;master&#34;,
                &#34;contentType&#34; : &#34;blueprint&#34;
              }
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        print(&#39;Successfully Created Blueprint Content Source&#39;)
        return &#39;Successfully Created Blueprint Content Source&#39;
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.create_cloud_flavor"><code class="name flex">
<span>def <span class="ident">create_cloud_flavor</span></span>(<span>url, username, password, flavor_name, mapping_name, cloud_instance_name, region_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Create Cloud Flavor
Abstracts cloud images and assigns a size value to them (e.g. - small, medium, large)</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>flavor_name = Provide a name for the Flavor(e.g. - small, medium, etc.)</p>
<p>size_name = Name</p>
<p>cloud_size_name = Name of Cloud Size (e.g.- AWS: t2.small , Azure: Standard_B1ms, vSphere: 2:4 - CPU:MEM)</p>
<p>region_name = Cloud Region (e.g. - Azure: eastus)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def create_cloud_flavor(url,username,password,flavor_name,mapping_name,cloud_instance_name,region_name):
    &#34;&#34;&#34;
    Create Cloud Flavor
    Abstracts cloud images and assigns a size value to them (e.g. - small, medium, large)

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    flavor_name = Provide a name for the Flavor(e.g. - small, medium, etc.)

    size_name = Name

    cloud_size_name = Name of Cloud Size (e.g.- AWS: t2.small , Azure: Standard_B1ms, vSphere: 2:4 - CPU:MEM)

    region_name = Cloud Region (e.g. - Azure: eastus)

    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username,password)
    reg_id = get_cloud_regionid_by_name(url,username,password,region_name)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/flavor-profiles&#39;.format(api_url_base)
    data =  {
                &#34;name&#34;: flavor_name,
                &#34;flavorMapping&#34;: {
                    mapping_name: {
                        &#34;name&#34;: cloud_instance_name
                    }
                },
                &#34;regionId&#34;: reg_id
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        print(&#39;Successfully Created Cloud Flavor&#39;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.create_cs_variable"><code class="name flex">
<span>def <span class="ident">create_cs_variable</span></span>(<span>url, username, password, name, proj_name, type, value, description=None)</span>
</code></dt>
<dd>
<div class="desc"><p>Creates a Code Stream variable</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA Admin user</p>
<p>password = vRA Admin password</p>
<p>name = Name of the Variable</p>
<p>proj_name = Name of the project the variable is assocaited</p>
<p>type = type of vairable to create (REGULAR / RESTRICTED / SECRET)</p>
<p>value = Value of the variable</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def create_cs_variable(url,username,password,name,proj_name,type,value,description=None):
    &#34;&#34;&#34;
    Creates a Code Stream variable

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    name = Name of the Variable

    proj_name = Name of the project the variable is assocaited

    type = type of vairable to create (REGULAR / RESTRICTED / SECRET)

    value = Value of the variable
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}codestream/api/variables&#39;.format(api_url_base)
    if description == None:
        description = &#34;&#34;
    data =  {
              &#34;description&#34;: description,
              &#34;name&#34;: name,
              &#34;project&#34;: proj_name,
              &#34;type&#34;: type,
              &#34;value&#34;: value
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#39;Successfully Created Code Stream Variable&#39;)
        return &#39;Successfully Created Code Stream Variable&#39;
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.create_github_saas_integration"><code class="name flex">
<span>def <span class="ident">create_github_saas_integration</span></span>(<span>url, username, password, name, private_key)</span>
</code></dt>
<dd>
<div class="desc"><p>Creates Github integration in Cloud Assembly</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA Admin user</p>
<p>password = vRA Admin password</p>
<p>name = Name of the Github integration (i.e. ABC Github)</p>
<p>private_key = Private key created in Github for secure access</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def create_github_saas_integration(url,username,password,name,private_key):
    &#34;&#34;&#34;
    Creates Github integration in Cloud Assembly

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    name = Name of the Github integration (i.e. ABC Github)

    private_key = Private key created in Github for secure access
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}provisioning/uerp/provisioning/mgmt/endpoints?external=&#39;.format(api_url_base)
    data =  {
                &#34;endpointProperties&#34;: {
                    &#34;url&#34;: &#34;www.github.com&#34;,
                    &#34;privateKey&#34;: private_key
                },
                &#34;customProperties&#34;: {
                    &#34;isExternal&#34;: &#34;true&#34;
                },
                &#34;endpointType&#34;: &#34;com.github.saas&#34;,
                &#34;name&#34;: name
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False, timeout=5)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        print(&#39;Successfully Created GitHub SaaS Integration&#39;)
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.create_image_mapping"><code class="name flex">
<span>def <span class="ident">create_image_mapping</span></span>(<span>url, username, password, profile_name, image_name, image_id, region_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Create Image Mapping.
An image mapping ties a cloud image (AWS = AMI, vSphere = Template) to a Cloud Zone Region</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>profile_name = The name of the image profile (i.e.vsphere-images)</p>
<p>image_name = The name of the image (i.e. Ubuntu)</p>
<p>image_id = name of the image instance (i.e. ami-03659409b9c7d0c5f or vsphere-ubuntu-template)</p>
<p>region_name = The datacenter id for the Cloud Account (i.e. Datacenter:datacenter-2 or eastus or us-west-1)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def create_image_mapping(url,username,password,profile_name,image_name,image_id,region_name):
    &#34;&#34;&#34;
    Create Image Mapping.
    An image mapping ties a cloud image (AWS = AMI, vSphere = Template) to a Cloud Zone Region

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    profile_name = The name of the image profile (i.e.vsphere-images)

    image_name = The name of the image (i.e. Ubuntu)

    image_id = name of the image instance (i.e. ami-03659409b9c7d0c5f or vsphere-ubuntu-template)

    region_name = The datacenter id for the Cloud Account (i.e. Datacenter:datacenter-2 or eastus or us-west-1)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username,password)
    reg_id = get_cloud_regionid_by_name(url,username,password,region_name)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/image-profiles&#39;.format(api_url_base)
    data =  {
              &#34;name&#34; : profile_name,
              &#34;description&#34;: &#34;Image Profile for &#34; + profile_name,
              &#34;imageMapping&#34; : {
                image_name: {
                  &#34;name&#34;: image_id
                }
              },
              &#34;regionId&#34;: reg_id
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        print(&#34;Successfully Created Image Mapping: &#34; + profile_name)
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.create_network_profile"><code class="name flex">
<span>def <span class="ident">create_network_profile</span></span>(<span>url, username, password, region_name, net_profile_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Create Network Profile.</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>net_profile_name = The name of the network profile (i.e.vsphere-networks)</p>
<p>region_name = The datacenter id for the Cloud Account (i.e. Datacenter:datacenter-2 or eastus or us-west-1)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def create_network_profile(url,username,password,region_name,net_profile_name):
    &#34;&#34;&#34;
    Create Network Profile.

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    net_profile_name = The name of the network profile (i.e.vsphere-networks)

    region_name = The datacenter id for the Cloud Account (i.e. Datacenter:datacenter-2 or eastus or us-west-1)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    reg_id = get_cloud_regionid_by_name(url,username,password,region_name)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/network-profiles&#39;.format(api_url_base)
    data = {
              &#34;isolationType&#34;: &#34;NONE&#34;,
              &#34;tags&#34;: [],
              &#34;customProperties&#34;: {
                &#34;datacenterId&#34;: region_name
              },
              &#34;name&#34;: net_profile_name,
              &#34;regionId&#34;: reg_id
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        print(&#39;Successfully Created Network Profile: &#39; + net_profile_name)
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.create_nsxt_ca"><code class="name flex">
<span>def <span class="ident">create_nsxt_ca</span></span>(<span>url, username, password, nsx_hostname, nsx_username, nsx_password, name, vc_ca_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Create NSX Cloud Account</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>nsx_hostname = FQDN of NSX Manager Instance</p>
<p>nsx_username = NSX Admin User</p>
<p>nsx_password = NSX Admin Password</p>
<p>name = Provide a name for the Cloud Account</p>
<p>vc_ca_name = Name of Cloud Account to associate with NSX Cloud Account</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def create_nsxt_ca(url,username,password,nsx_hostname,nsx_username,nsx_password,name,vc_ca_name):
    &#34;&#34;&#34;
    Create NSX Cloud Account

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    nsx_hostname = FQDN of NSX Manager Instance

    nsx_username = NSX Admin User

    nsx_password = NSX Admin Password

    name = Provide a name for the Cloud Account

    vc_ca_name = Name of Cloud Account to associate with NSX Cloud Account
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    ca_json = get_ca_by_name(url,username,password,vc_ca_name)
    ca_id = ca_json[&#39;id&#39;]
    ca_array = []
    ca_array.append(ca_id)
    api_url = &#39;{0}iaas/api/cloud-accounts-nsx-t&#39;.format(api_url_base)
    data = {
              &#34;hostName&#34;: nsx_hostname,
              &#34;acceptSelfSignedCertificate&#34;: &#34;true&#34;,
              &#34;password&#34;: nsx_password,
              &#34;dcid&#34;: &#34;onprem&#34;,
              &#34;associatedCloudAccountIds&#34;: ca_array,
              &#34;managerMode&#34;: &#34;true&#34;,
              &#34;name&#34;: name,
              &#34;description&#34;: &#34;NSX-T Cloud Account&#34;,
              &#34;username&#34;: nsx_username
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        print(&#39;Successfully Created NSX-T Cloud Account&#39;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.create_project"><code class="name flex">
<span>def <span class="ident">create_project</span></span>(<span>url, username, password, name)</span>
</code></dt>
<dd>
<div class="desc"><p>Create a Project</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA Admin user</p>
<p>password = vRA Admin password</p>
<p>name = Name of the Project</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def create_project(url,username,password,name):
    &#34;&#34;&#34;
    Create a Project

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    name = Name of the Project
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/projects&#39;.format(api_url_base)
    data =  {
              &#34;administrators&#34;: [],
              &#34;members&#34;: [],
              &#34;operationTimeout&#34;: 0,
              &#34;sharedResources&#34;: &#34;true&#34;,
              &#34;name&#34;: name,
              &#34;description&#34;: &#34;Project for &#34; + name
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        print(&#39;Successfully Created Project&#39;)
        return json_data[&#39;id&#39;]
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.create_sb_content_source"><code class="name flex">
<span>def <span class="ident">create_sb_content_source</span></span>(<span>url, username, password, proj_name, content_source_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Adds Entitlement to the Project for a Service Broker content source</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA Admin user</p>
<p>password = vRA Admin password</p>
<p>proj_name = vRA Project name</p>
<p>content_source_name = The name used to create the content source in Service Broker</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def create_sb_content_source(url,username,password,proj_name,content_source_name):
    &#34;&#34;&#34;
    Adds Entitlement to the Project for a Service Broker content source

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    proj_name = vRA Project name

    content_source_name = The name used to create the content source in Service Broker
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    proj_json = get_proj_by_name(url,username,password,proj_name)
    proj_id = proj_json[&#39;id&#39;]
    cs_json = get_sb_content_source_by_name(url,username,password,content_source_name)
    cs_id = cs_json[&#39;id&#39;]
    api_url = &#39;{0}catalog/api/admin/entitlements&#39;.format(api_url_base)
    data =  {
              &#34;projectId&#34;: proj_id,
              &#34;definition&#34;: {
                &#34;id&#34;: cs_id,
                &#34;sourceName&#34;: content_source_name,
                &#34;type&#34;: &#34;CatalogSourceIdentifier&#34;
              }
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        print(&#39;Successfully Entitled Content Source: &#39; + content_source_name)
        return &#39;Successfully Entitled Content Source: &#39; + content_source_name
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.create_template_version"><code class="name flex">
<span>def <span class="ident">create_template_version</span></span>(<span>url, username, password, template_name, version, release='false', change_log=None)</span>
</code></dt>
<dd>
<div class="desc"><p>Creates a version of the cloud template</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA Admin user</p>
<p>password = vRA Admin password</p>
<p>template_name = Name of the cloud template to find</p>
<p>version = version for the template (i.e. 1.1)</p>
<p>release = Release the version to the Service Broker catalog (true / false (default))</p>
<p>change_log = Description of changes to template (if not included the change log is left blank)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def create_template_version(url,username,password,template_name,version,release=&#34;false&#34;,change_log=None):
    &#34;&#34;&#34;
    Creates a version of the cloud template

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    template_name = Name of the cloud template to find

    version = version for the template (i.e. 1.1)

    release = Release the version to the Service Broker catalog (true / false (default))

    change_log = Description of changes to template (if not included the change log is left blank)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    template_json = get_template_by_name(url,username,password,template_name)
    template_id = template_json[&#39;id&#39;]
    api_url = &#39;{0}blueprint/api/blueprints/{1}/versions&#39;.format(api_url_base,template_id)
    if change_log == None:
        change_log = &#34;&#34;
    data =  {
              &#34;changeLog&#34;: change_log,
              &#34;description&#34;: &#34;Created version &#34; + version + &#34; of Template&#34;,
              &#34;release&#34;: release,
              &#34;version&#34;: version
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        print(&#39;Successfully Created Version of Cloud Template&#39;)
        return &#39;Successfully Created Version of Cloud Template&#39;
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.create_vsphere_ca"><code class="name flex">
<span>def <span class="ident">create_vsphere_ca</span></span>(<span>url, username, password, vc_hostname, vc_username, vc_password, name, region_id)</span>
</code></dt>
<dd>
<div class="desc"><p>Setup and Create vSphere Cloud Account</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>vc_hostname = vCenter IP / FQDN</p>
<p>vc_username: vCenter Administrator User</p>
<p>vc_password = vCenter Password</p>
<p>name = Cloud Account Name</p>
<p>region_id = vCenter Datacenter (i.e. Datacenter:datacenter-2)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def create_vsphere_ca(url,username,password,vc_hostname,vc_username,vc_password,name,region_id):
    &#34;&#34;&#34;
    Setup and Create vSphere Cloud Account

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    vc_hostname = vCenter IP / FQDN

    vc_username: vCenter Administrator User

    vc_password = vCenter Password

    name = Cloud Account Name

    region_id = vCenter Datacenter (i.e. Datacenter:datacenter-2)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/cloud-accounts-vsphere&#39;.format(api_url_base)
    data = {
              &#34;name&#34;: name,
              &#34;hostName&#34;: vc_hostname,
              &#34;acceptSelfSignedCertificate&#34;: &#34;true&#34;,
              &#34;dcid&#34;: &#34;onprem&#34;,
              &#34;username&#34;: vc_username,
              &#34;password&#34;: vc_password,
              &#34;regionIds&#34;: [
                region_id
              ],
              &#34;createDefaultZones&#34;: &#34;true&#34;
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        print(&#39;Successfully Created vCenter Cloud Account&#39;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.create_vsphere_flavor"><code class="name flex">
<span>def <span class="ident">create_vsphere_flavor</span></span>(<span>url, username, password, flavor_name, mapping_name, cpu_count, mem_count, region_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Create vSphere Flavor
vSphere Flavor is a size of an image, t-shirt sizing"</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>flavor_name = Name of the Flavor Mapping (i.e. vsphere)</p>
<p>mapping_name = The name that displays in Cloud Assembly for the flavor (i.e.Small)</p>
<p>cpu_count = number of CPUs assigned using this flavor (i.e. 2)</p>
<p>mem_count = amount of memory assigned using this flavor in GB (i.e. 4)</p>
<p>region_name = The datacenter id for the Cloud Account (i.e. Datacenter:datacenter-2)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def create_vsphere_flavor(url,username,password,flavor_name,mapping_name,cpu_count,mem_count,region_name):
    &#34;&#34;&#34;
    Create vSphere Flavor
    vSphere Flavor is a size of an image, t-shirt sizing&#34;

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    flavor_name = Name of the Flavor Mapping (i.e. vsphere)

    mapping_name = The name that displays in Cloud Assembly for the flavor (i.e.Small)

    cpu_count = number of CPUs assigned using this flavor (i.e. 2)

    mem_count = amount of memory assigned using this flavor in GB (i.e. 4)

    region_name = The datacenter id for the Cloud Account (i.e. Datacenter:datacenter-2)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username,password)
    reg_id = get_cloud_regionid_by_name(url,username,password,region_name)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/flavor-profiles&#39;.format(api_url_base)
    data =  {
                &#34;name&#34;: flavor_name,
                &#34;flavorMapping&#34;: {
                    mapping_name: {
                        &#34;cpuCount&#34;: cpu_count,
                        &#34;memoryInMB&#34;: mem_count
                    }
                },
                &#34;regionId&#34;: reg_id
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        print(&#39;Successfully Created vSphere Flavor&#39;)
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.create_vsphere_storage_profile"><code class="name flex">
<span>def <span class="ident">create_vsphere_storage_profile</span></span>(<span>url, username, password, name, region_name, datastore_name, encrypted='false', sharelevel='normal', diskmode='independent-persistent', tag_key=None, iops_limit=None, tag_value=None, shares='1000', provision_type='thin', default='false', disktype='standard', policy_name=None)</span>
</code></dt>
<dd>
<div class="desc"><p>Creates a vSphere Storage Profile</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA Admin user</p>
<p>password = vRA Admin password</p>
<p>name = Name of the Storage Profile</p>
<p>region_name = Name of the region this profile is attached (i.e Datacenter:datacenter-2)</p>
<p>datastor_name = Name of the datastore to assign to profile</p>
<p>encrypted = is datastore encrypted (true or false(default))</p>
<p>sharelevel = Sets the share level (unspecified / low / normal(default) / high / custom)</p>
<p>diskmode = Sets the disk mode for the profile (dependent / independent-persistent(default) / independent-nonpersistent)</p>
<p>tag_key = Key for the tag (i.e. env:tag_value)</p>
<p>tag_value = Value for the tag (i.e. tag_key:vsphere)</p>
<p>iops_limit = Sets the IOPs limit for the Storage profile (if not set value is set to unlimited)</p>
<p>shares = Sets the shares value for the storage profile (default is 1000)</p>
<p>provision_type = Sets the provisioning type for the storage profile (unspecified / thin / thick / eagerZeroedThick)</p>
<p>default = Is this the default profile for the region (true / false (default))</p>
<p>disk_type = Type of disk for this profile (standard (default) / fcd)</p>
<p>policy_name = The name of the storage policy from vCenter to use for this profile (if argument not added then datastore default policy is applied)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def create_vsphere_storage_profile(url,username,password,name,region_name,datastore_name,encrypted=&#34;false&#34;,sharelevel=&#34;normal&#34;,diskmode=&#34;independent-persistent&#34;,tag_key=None,iops_limit=None,tag_value=None,shares=&#34;1000&#34;,provision_type=&#34;thin&#34;,default=&#34;false&#34;,disktype=&#34;standard&#34;,policy_name=None):
    &#34;&#34;&#34;
    Creates a vSphere Storage Profile

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    name = Name of the Storage Profile

    region_name = Name of the region this profile is attached (i.e Datacenter:datacenter-2)

    datastor_name = Name of the datastore to assign to profile

    encrypted = is datastore encrypted (true or false(default))

    sharelevel = Sets the share level (unspecified / low / normal(default) / high / custom)

    diskmode = Sets the disk mode for the profile (dependent / independent-persistent(default) / independent-nonpersistent)

    tag_key = Key for the tag (i.e. env:tag_value)

    tag_value = Value for the tag (i.e. tag_key:vsphere)

    iops_limit = Sets the IOPs limit for the Storage profile (if not set value is set to unlimited)

    shares = Sets the shares value for the storage profile (default is 1000)

    provision_type = Sets the provisioning type for the storage profile (unspecified / thin / thick / eagerZeroedThick)

    default = Is this the default profile for the region (true / false (default))

    disk_type = Type of disk for this profile (standard (default) / fcd)

    policy_name = The name of the storage policy from vCenter to use for this profile (if argument not added then datastore default policy is applied)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    reg_id = get_cloud_regionid_by_name(url,username,password,region_name)
    if tag_key != None:
        if tag_value != None:
            tag_prep = {&#34;key&#34;: tag_key,&#34;value&#34;: tag_value}
            tag = []
            tag.append(tag_prep)
    else:
        tag = []
    ds_json = get_vsphere_datastore_by_name(url,username,password,datastore_name)
    ds_id = ds_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/storage-profiles-vsphere&#39;.format(api_url_base)
    payload = {
              &#34;supportsEncryption&#34;: encrypted,
              &#34;sharesLevel&#34;: sharelevel,
              &#34;description&#34;: &#34;vSphere Storage&#34;,
              &#34;diskMode&#34;: diskmode,
              &#34;tags&#34;: tag,
              &#34;shares&#34;: shares,
              &#34;provisioningType&#34;: provision_type,
              &#34;regionId&#34;: reg_id,
              &#34;name&#34;: name,
              &#34;defaultItem&#34;: default,
              &#34;diskType&#34;: disktype,
              &#34;datastoreId&#34;: ds_id
            }
    if policy_name != None:
        policy_id = get_storage_policy_id_by_name(url,username,password,policy_name)
        a = json.dumps(payload)
        a = a[1:-1]
        policy = {&#34;storagePolicyId&#34;: policy_id}
        b = json.dumps(policy)
        b = b[1:-1]
        combined = a + &#34;,&#34; + b
        payload = &#34;{&#34; + combined + &#34;}&#34;
        payload = json.loads(payload)
    if iops_limit != None:
        c = json.dumps(payload)
        c = c[1:-1]
        iops = {&#34;limitIops&#34;: iops_limit}
        d = json.dumps(iops)
        d = d[1:-1]
        combined = c + &#34;,&#34; + d
        payload = &#34;{&#34; + combined + &#34;}&#34;
        payload = json.loads(payload)
    data = payload
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 201:
        print(&#39;Successfully Created vSphere Storage Profile&#39;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.delete_cloudaccount"><code class="name flex">
<span>def <span class="ident">delete_cloudaccount</span></span>(<span>url, username, password, ca_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Delete Cloud Account</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>ca_name = Cloud Account Name</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def delete_cloudaccount(url,username,password,ca_name):
    &#34;&#34;&#34;
    Delete Cloud Account

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    ca_name = Cloud Account Name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    ca_json = get_ca_by_name(url,username,password,czname)
    ca_id = ca_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/zones/{1}&#39;.format(api_url_base,ca_id)
    response = requests.delete(api_url, headers=headers, verify=False)
    if response.status_code == 204:
        print(&#39;Successfully Deleted Cloud Account: &#39; + czname)
        return &#39;Successfully Deleted Cloud Account: &#39; + czname
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.delete_cloudzone"><code class="name flex">
<span>def <span class="ident">delete_cloudzone</span></span>(<span>url, username, password, czname)</span>
</code></dt>
<dd>
<div class="desc"><p>Delete Cloud Zone</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>czname = Cloud Zone Name</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def delete_cloudzone(url,username,password,czname):
    &#34;&#34;&#34;
    Delete Cloud Zone

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    czname = Cloud Zone Name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    czid = get_czid_by_name(url,username,password,czname)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/zones/{1}&#39;.format(api_url_base,czid)
    response = requests.delete(api_url, headers=headers, verify=False)
    if response.status_code == 204:
        print(&#39;Successfully Deleted Cloud Zone: &#39; + czname)
        return &#39;Successfully Deleted Cloud Zone: &#39; + czname
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.delete_flavor_mapping"><code class="name flex">
<span>def <span class="ident">delete_flavor_mapping</span></span>(<span>url, username, password, flavor_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Delete Flavor Mapping</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>flavor_name = Flavor name</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def delete_flavor_mapping(url,username,password,flavor_name):
    &#34;&#34;&#34;
    Delete Flavor Mapping

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    flavor_name = Flavor name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    flav_json = get_flavor_by_name(url,username,password,flavor_name)
    flav_id = flav_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/flavor-profiles/{1}&#39;.format(api_url_base,flav_id)
    response = requests.delete(api_url, headers=headers, verify=False)
    if response.status_code == 204:
        print(&#39;Successfully Deleted Flavor Mapping: &#39; + flavor_name)
        return &#39;Successfully Deleted Flavor Mapping: &#39; + flavor_name
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.delete_image_mapping"><code class="name flex">
<span>def <span class="ident">delete_image_mapping</span></span>(<span>url, username, password, profile_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Delete Image Mapping</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>profile_name = Image Profile Name</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def delete_image_mapping(url,username,password,profile_name):
    &#34;&#34;&#34;
    Delete Image Mapping

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    profile_name = Image Profile Name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    img_json = get_image_profile_by_name(url,username,password,profile_name)
    img_id = img_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/image-profiles/{1}&#39;.format(api_url_base,img_id)
    response = requests.delete(api_url, headers=headers, verify=False)
    if response.status_code == 204:
        print(&#39;Successfully Deleted Flavor Mapping: &#39; + profile_name)
        return &#39;Successfully Deleted Flavor Mapping: &#39; + profile_name
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.delete_integration_by_name"><code class="name flex">
<span>def <span class="ident">delete_integration_by_name</span></span>(<span>url, username, password, int_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Delete Integration in vRA Cloud Assembly</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>int_name = Integration Name</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def delete_integration_by_name(url,username,password,int_name):
    &#34;&#34;&#34;
    Delete Integration in vRA Cloud Assembly

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    int_name = Integration Name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    int_id = get_integration_by_name(url,username,password,int_name)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}provisioning/uerp/resources/endpoints/{1}&#39;.format(api_url_base,cs_id)
    response = requests.delete(api_url, headers=headers, verify=False)
    if response.status_code == 204:
        print(&#39;Successfully Deleted Integration in Cloud Assembly: &#39; + content_source_name)
        return &#39;Successfully Deleted Integration in Cloud Assembly: &#39; + content_source_name
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.delete_netprofile"><code class="name flex">
<span>def <span class="ident">delete_netprofile</span></span>(<span>url, username, password, net_profile_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Delete Network Profile</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>net_profile_name = Network Profile Name</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def delete_netprofile(url,username,password,net_profile_name):
    &#34;&#34;&#34;
    Delete Network Profile

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    net_profile_name = Network Profile Name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    net_json = get_netprofile_by_name(url,username,password,net_profile_name)
    net_id = net_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/network-profiles/{1}&#39;.format(api_url_base,net_id)
    response = requests.delete(api_url, headers=headers, verify=False)
    if response.status_code == 204:
        print(&#39;Successfully Deleted Network Profile: &#39; + net_profile_name)
        return &#39;Successfully Deleted Network profile: &#39; + net_profile_name
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.delete_project"><code class="name flex">
<span>def <span class="ident">delete_project</span></span>(<span>url, username, password, projname)</span>
</code></dt>
<dd>
<div class="desc"><p>Delete Project</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>proj_name = Provide name of a Project to Delete</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def delete_project(url,username,password,projname):
    &#34;&#34;&#34;
    Delete Project

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    proj_name = Provide name of a Project to Delete
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    proj_json = get_proj_by_name(url,username,password,projname)
    proj_id = proj_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/projects/{1}&#39;.format(api_url_base,proj_id)
    response = requests.delete(api_url, headers=headers, verify=False)
    if response.status_code == 204:
        print(&#39;Successfully Deleted Project: &#39; + projname)
        return &#39;Successfully Deleted Project: &#39; + projname
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.delete_sb_content_source"><code class="name flex">
<span>def <span class="ident">delete_sb_content_source</span></span>(<span>url, username, password, content_source_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Delete Service Broker Content Source</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>content_source_name = Content Source Name</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def delete_sb_content_source(url,username,password,content_source_name):
    &#34;&#34;&#34;
    Delete Service Broker Content Source

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    content_source_name = Content Source Name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    cs_json = get_sb_content_source_by_name(url,username,password,content_source_name)
    cs_id = cs_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}catalog/api/admin/sources/{1}&#39;.format(api_url_base,cs_id)
    response = requests.delete(api_url, headers=headers, verify=False)
    if response.status_code == 204:
        print(&#39;Successfully Deleted Service Broker Content Source: &#39; + content_source_name)
        return &#39;Successfully Deleted Service Broker Content Source: &#39; + content_source_name
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.delete_storage_profile"><code class="name flex">
<span>def <span class="ident">delete_storage_profile</span></span>(<span>url, username, password, storage_profile_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Delete Storage Profile</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>storage_profile_name = Storage Profile Name</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def delete_storage_profile(url,username,password,storage_profile_name):
    &#34;&#34;&#34;
    Delete Storage Profile

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    storage_profile_name = Storage Profile Name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    sp_json = get_storage_profile_by_name(url,username,password,storage_profile_name)
    sp_id = sp_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/storage-profiles/{1}&#39;.format(api_url_base,sp_id)
    response = requests.delete(api_url, headers=headers, verify=False)
    if response.status_code == 204:
        print(&#39;Successfully Deleted Storage Profile: &#39; + storage_profile_name)
        return &#39;Successfully Deleted Storage Profile: &#39; + storage_profile_name
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.delete_template"><code class="name flex">
<span>def <span class="ident">delete_template</span></span>(<span>url, username, password, template_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Delete Cloud Template</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>template_name = Cloud Template Name</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def delete_template(url,username,password,template_name):
    &#34;&#34;&#34;
    Delete Cloud Template

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    template_name = Cloud Template Name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    temp_json = get_template_by_name(url,username,password,template_name)
    temp_id = temp_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}blueprint/api/blueprints/{1}&#39;.format(api_url_base,temp_id)
    response = requests.delete(api_url, headers=headers, verify=False)
    if response.status_code == 204:
        print(&#39;Successfully Deleted Cloud Template: &#39; + template_name)
        return &#39;Successfully Deleted Cloud Template: &#39; + template_name
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.delete_variable"><code class="name flex">
<span>def <span class="ident">delete_variable</span></span>(<span>url, username, password, variable_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Delete Code Stream Variable</p>
<p>Arguments:
url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>variable_name = Variable Name</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def delete_variable(url,username,password,variable_name):
    &#34;&#34;&#34;
    Delete Code Stream Variable

    Arguments:
    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    variable_name = Variable Name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    var_id = get_variable_by_name(url,username,password,variable_name)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}codestream/api/variables/{1}&#39;.format(api_url_base,var_id)
    response = requests.delete(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        print(&#39;Successfully Deleted Code Stream Variable: &#39; + variable_name)
        return &#39;Successfully Deleted Code Stream Variable: &#39; + variable_name
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.disable_tf_on_project"><code class="name flex">
<span>def <span class="ident">disable_tf_on_project</span></span>(<span>url, username, password, projname)</span>
</code></dt>
<dd>
<div class="desc"><p>Disable Terraform on Project</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>projname = Provide name of a Project to remove the Terraform service</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def disable_tf_on_project(url,username,password,projname):
    &#34;&#34;&#34;
    Disable Terraform on Project

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    projname = Provide name of a Project to remove the Terraform service
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    proj_json = get_proj_by_name(url,username,password,projname)
    proj_id = proj_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}project-service/api/projects/{1}&#39;.format(api_url_base,proj_id)
    data =  {
              &#34;properties&#34;: {
              }
            }
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#34;Successfully disabled Terraform Service on project: &#34; + projname)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.enable_tf_on_project"><code class="name flex">
<span>def <span class="ident">enable_tf_on_project</span></span>(<span>url, username, password, projname)</span>
</code></dt>
<dd>
<div class="desc"><p>Enable Terraform Service on a Project</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>projname: Provide name of a Project to add the Terraform service</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def enable_tf_on_project(url,username,password,projname):
    &#34;&#34;&#34;
    Enable Terraform Service on a Project

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    projname: Provide name of a Project to add the Terraform service
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    proj_json = get_proj_by_name(url,username,password,projname)
    proj_id = proj_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}project-service/api/projects/{1}&#39;.format(api_url_base,proj_id)
    data =  {
              &#34;properties&#34;: {
                 &#34;__allowTerraformCloudzoneMapping&#34;: &#34;true&#34;
              }
            }
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#34;Successfully enabled Terraform Service on project: &#34; + projname)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.extract_values"><code class="name flex">
<span>def <span class="ident">extract_values</span></span>(<span>obj, key)</span>
</code></dt>
<dd>
<div class="desc"><p>Pull all values of specified key from nested JSON.</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def extract_values(obj, key):
    &#34;&#34;&#34;
    Pull all values of specified key from nested JSON.
    &#34;&#34;&#34;
    arr = []
    def extract(obj, arr, key):
        &#34;&#34;&#34;Recursively search for values of key in JSON tree.&#34;&#34;&#34;
        if isinstance(obj, dict):
            for k, v in obj.items():
                if isinstance(v, (dict, list)):
                    extract(v, arr, key)
                elif k == key:
                    arr.append(v)
        elif isinstance(obj, list):
            for item in obj:
                extract(item, arr, key)
        return arr
    results = extract(obj, arr, key)
    return results</code></pre>
</details>
</dd>
<dt id="vra_module.get_ca_by_name"><code class="name flex">
<span>def <span class="ident">get_ca_by_name</span></span>(<span>url, username, password, vc_ca_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Retrieve Cloud Account by its names for further configurations</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>vc_ca_name = Cloud Account Name</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def get_ca_by_name(url,username,password,vc_ca_name):
    &#34;&#34;&#34;
    Retrieve Cloud Account by its names for further configurations

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    vc_ca_name = Cloud Account Name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/cloud-accounts&#39;.format(api_url_base,vc_ca_name)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            ca_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if ca_name == vc_ca_name:
                print(&#34;Found Cloud Account: &#34; + vc_ca_name)
                ca_json = json_data[&#39;content&#39;][n]
                return ca_json
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For Cloud Zone: &#34; + vc_ca_name)
                return &#34;No Match Found For Cloud Zone: &#34; + vc_ca_name
                break
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.get_cloud_acct_type"><code class="name flex">
<span>def <span class="ident">get_cloud_acct_type</span></span>(<span>url, username, password, caid)</span>
</code></dt>
<dd>
<div class="desc"><p>Returns the type of Cloud Account based on id. (used to determine NSX resources)</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>caid = Cloud Account ID</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def get_cloud_acct_type(url,username,password,caid):
    &#34;&#34;&#34;
    Returns the type of Cloud Account based on id. (used to determine NSX resources)

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    caid = Cloud Account ID
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/cloud-accounts/{1}&#39;.format(api_url_base,caid)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        ca_type = extract_values(json_data,&#39;cloudAccountType&#39;)
        return ca_type
    else:
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.get_cloud_regionid_by_name"><code class="name flex">
<span>def <span class="ident">get_cloud_regionid_by_name</span></span>(<span>url, username, password, region_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Get Cloud Region Id for Further Configurations</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>region_name = Provide a name of Region to search for</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def get_cloud_regionid_by_name(url,username,password,region_name):
    &#34;&#34;&#34;
    Get Cloud Region Id for Further Configurations

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    region_name = Provide a name of Region to search for

    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/regions&#39;.format(api_url_base,region_name)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            reg_name = json_data[&#39;content&#39;][n][&#39;externalRegionId&#39;]
            if reg_name == region_name:
                print(&#34;Found Cloud Zone: &#34; + region_name)
                reg_id = json_data[&#39;content&#39;][n][&#39;id&#39;]
                return reg_id
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For Cloud Zone: &#34; + region_name)
                return &#34;No Match Found For Cloud Zone: &#34; + region_name
                break
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.get_czid_by_name"><code class="name flex">
<span>def <span class="ident">get_czid_by_name</span></span>(<span>url, username, password, czname)</span>
</code></dt>
<dd>
<div class="desc"><p>Retrieve Cloud Zone by Name for further configurations</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>czname = Cloud Zone Name</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def get_czid_by_name(url,username,password,czname):
    &#34;&#34;&#34;
    Retrieve Cloud Zone by Name for further configurations

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    czname = Cloud Zone Name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/zones&#39;.format(api_url_base,czname)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            cz_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if cz_name == czname:
                print(&#34;Found Cloud Zone: &#34; + czname)
                cz_id = json_data[&#39;content&#39;][n][&#39;id&#39;]
                return cz_id
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For Cloud Zone: &#34; + czname)
                return &#34;No Match Found For Cloud Zone: &#34; + czname
                break
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.get_fabric_network_by_name"><code class="name flex">
<span>def <span class="ident">get_fabric_network_by_name</span></span>(<span>url, username, password, fabric_net_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Get discovered network by name and return information via json.</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>fabric_net_name = The name of the network that was discovered by vRA discover service (i.e.web-network)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def get_fabric_network_by_name(url,username,password,fabric_net_name):
    &#34;&#34;&#34;
    Get discovered network by name and return information via json.

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    fabric_net_name = The name of the network that was discovered by vRA discover service (i.e.web-network)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/fabric-networks&#39;.format(api_url_base,fabric_net_name)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            net_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if net_name == fabric_net_name:
                print(&#34;Found Frabric Network: &#34; + fabric_net_name)
                fabnet_id = json_data[&#39;content&#39;][n]
                return fabnet_id
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For Frabric Network: &#34; + fabric_net_name)
                break
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.get_flavor_by_name"><code class="name flex">
<span>def <span class="ident">get_flavor_by_name</span></span>(<span>url, username, password, flavor_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Get Flavor by name for further configurations</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>flavor_name = Name of the Flavor Mapping</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def get_flavor_by_name(url,username,password,flavor_name):
    &#34;&#34;&#34;
    Get Flavor by name for further configurations

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    flavor_name = Name of the Flavor Mapping
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/flavor-profiles&#39;.format(api_url_base,flavor_name)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            flav_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if flav_name == flavor_name:
                print(&#34;Found Flavor Mapping: &#34; + flavor_name)
                return json_data[&#39;content&#39;][n]
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For Flavor Mapping: &#34; + flavor_name)
                return &#34;No Match Found For Flavor Mapping: &#34; + flavor_name
                break
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.get_image_profile_by_name"><code class="name flex">
<span>def <span class="ident">get_image_profile_by_name</span></span>(<span>url, username, password, profile_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Gets image mapping by name and reutns information via json</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>profile_name = The name of the image profile (i.e.vsphere-images)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def get_image_profile_by_name(url,username,password,profile_name):
    &#34;&#34;&#34;
    Gets image mapping by name and reutns information via json

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    profile_name = The name of the image profile (i.e.vsphere-images)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/image-profiles&#39;.format(api_url_base,profile_name)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            img_prof_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if img_prof_name == profile_name:
                print(&#34;Found Image Mapping: &#34; + profile_name)
                return json_data[&#39;content&#39;][n]
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For Flavor Mapping: &#34; + flavor_name)
                return &#34;No Match Found For Flavor Mapping: &#34; + flavor_name
                break
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.get_integration_by_name"><code class="name flex">
<span>def <span class="ident">get_integration_by_name</span></span>(<span>url, username, password, int_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Gits a Cloud Assembly Integration by name and returns information via json</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA Admin user</p>
<p>password = vRA Admin password</p>
<p>int_name = Name of the Integration in Cloud Assembly (i.e. ABC Github)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def get_integration_by_name(url,username,password,int_name):
    &#34;&#34;&#34;
    Gits a Cloud Assembly Integration by name and returns information via json

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    int_name = Name of the Integration in Cloud Assembly (i.e. ABC Github)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}provisioning/uerp/resources/endpoints&#39;.format(api_url_base)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        endpoint_links = json_data[&#39;documentLinks&#39;]
        for x in endpoint_links:
            api_url = &#39;{0}provisioning/uerp{1}&#39;.format(api_url_base,x)
            response = requests.get(api_url, headers=headers, verify=False)
            if response.status_code == 200:
                json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
                integration_name = json_data[&#39;name&#39;]
                if integration_name == int_name:
                    print(&#34;Found Integration by name: &#34; + int_name)
                    int_id = x[21:]
                    return int_id
            else:
                print(&#34;Inner Rest call for get_nsxt_router_link_by_name failed with error: &#34; + response.status_code)
                return (&#34;Inner Rest call for get_nsxt_router_link_by_name failed with error: &#34; + response.status_code)
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.get_netprofile_by_name"><code class="name flex">
<span>def <span class="ident">get_netprofile_by_name</span></span>(<span>url, username, password, net_profile_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Get existing Network Profile by name and return information via json.</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>net_profile_name = The name of the network profile (i.e.vsphere-networks)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def get_netprofile_by_name(url,username,password,net_profile_name):
    &#34;&#34;&#34;
    Get existing Network Profile by name and return information via json.

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    net_profile_name = The name of the network profile (i.e.vsphere-networks)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/network-profiles&#39;.format(api_url_base,net_profile_name)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            prof_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if prof_name == net_profile_name:
                print(&#34;Found Network Profile: &#34; + net_profile_name)
                prof_id = json_data[&#39;content&#39;][n]
                return prof_id
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For Network Profile: &#34; + net_profile_name)
                break
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.get_nsxt_fabric_network_by_name"><code class="name flex">
<span>def <span class="ident">get_nsxt_fabric_network_by_name</span></span>(<span>url, username, password, fabric_net_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Get discovered NSX-T network by name and return information via json.</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>fabric_net_name = The name of the network that was discovered by vRA discover service (i.e.web-network)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def get_nsxt_fabric_network_by_name(url,username,password,fabric_net_name):
    &#34;&#34;&#34;
    Get discovered NSX-T network by name and return information via json.

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    fabric_net_name = The name of the network that was discovered by vRA discover service (i.e.web-network)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/fabric-networks&#39;.format(api_url_base,fabric_net_name)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            net_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if net_name == fabric_net_name:
                print(&#34;Found Frabric Network: &#34; + fabric_net_name)
                ca_type = get_cloud_acct_type(url,username,password,json_data[&#39;content&#39;][n][&#39;cloudAccountIds&#39;][0])
                if ca_type[0] == &#34;nsxt&#34;:
                    print(&#34;Fabric Network is type NSXT&#34;)
                    fabnet_id = json_data[&#39;content&#39;][n]
                    return fabnet_id
                    break
                elif n &lt; end_n:
                    print(&#34;Frabric Network is not type NSXT&#34;)
                    n = n + 1
                elif n &gt;= end_n:
                    print(&#34;No Match Found For NSXT Frabric Network: &#34; + fabric_net_name)
                    break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For NSXT Frabric Network: &#34; + fabric_net_name)
                break
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.get_nsxt_router_link_by_name"><code class="name flex">
<span>def <span class="ident">get_nsxt_router_link_by_name</span></span>(<span>url, username, password, router_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Gets the document link to the NSX-T router by name and return the link</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA Admin user</p>
<p>password = vRA Admin password</p>
<p>router_name = Name of the router in NSX-T (i.e. T0-router)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def get_nsxt_router_link_by_name(url,username,password,router_name):
    &#34;&#34;&#34;
    Gets the document link to the NSX-T router by name and return the link

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    router_name = Name of the router in NSX-T (i.e. T0-router)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}provisioning/uerp/resources/routers&#39;.format(api_url_base)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        router_links = json_data[&#39;documentLinks&#39;]
        for x in router_links:
            api_url = &#39;{0}provisioning/uerp{1}&#39;.format(api_url_base,x)
            response = requests.get(api_url, headers=headers, verify=False)
            if response.status_code == 200:
                json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
                rtr_name = json_data[&#39;name&#39;]
                if rtr_name == router_name:
                    print(&#34;Found NSXT Router by name: &#34; + router_name)
                    return x
            else:
                print(&#34;Inner Rest call for get_nsxt_router_link_by_name failed with error: &#34; + response.status_code)
                return (&#34;Inner Rest call for get_nsxt_router_link_by_name failed with error: &#34; + response.status_code)
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.get_proj_by_name"><code class="name flex">
<span>def <span class="ident">get_proj_by_name</span></span>(<span>url, username, password, projname)</span>
</code></dt>
<dd>
<div class="desc"><p>Get Project by Name</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA Admin user</p>
<p>password = vRA Admin password</p>
<p>projname: Name of the Project to search for</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def get_proj_by_name(url,username,password,projname):
    &#34;&#34;&#34;
    Get Project by Name

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    projname: Name of the Project to search for
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/projects&#39;.format(api_url_base,projname)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            proj_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if proj_name == projname:
                print(&#34;Found Project: &#34; + projname)
                proj_id = json_data[&#39;content&#39;][n]
                return proj_id
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For Project: &#34; + projname)
                break
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.get_sb_content_source_by_name"><code class="name flex">
<span>def <span class="ident">get_sb_content_source_by_name</span></span>(<span>url, username, password, content_source_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Finds the Service Broker content source by name and returns information via json</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA Admin user</p>
<p>password = vRA Admin password</p>
<p>content_source_name = The name used to create the content source in Service Broker</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def get_sb_content_source_by_name(url,username,password,content_source_name):
    &#34;&#34;&#34;
    Finds the Service Broker content source by name and returns information via json

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    content_source_name = The name used to create the content source in Service Broker
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}catalog/api/admin/sources&#39;.format(api_url_base)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;numberOfElements&#39;]
        end_n = end_n - 1
        while True:
            source_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if source_name == content_source_name:
                print(&#34;Found Content Source: &#34; + content_source_name)
                source_id = json_data[&#39;content&#39;][n]
                return source_id
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For Frabric Network: &#34; + content_source_name)
                break
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.get_sec_group_by_name"><code class="name flex">
<span>def <span class="ident">get_sec_group_by_name</span></span>(<span>url, username, password, secgroup_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Get discovered security group by name and return information via json.</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>secgroup_name = The name of the existing security group (i.e.web-security)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def get_sec_group_by_name(url,username,password,secgroup_name):
    &#34;&#34;&#34;
    Get discovered security group by name and return information via json.

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    secgroup_name = The name of the existing security group (i.e.web-security)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/security-groups&#39;.format(api_url_base,secgroup_name)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            sg_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if sg_name == secgroup_name:
                print(&#34;Found Security Group: &#34; + secgroup_name)
                sg_id = json_data[&#39;content&#39;][n][&#39;id&#39;]
                return sg_id
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For Security Group: &#34; + secgroup_name)
                break
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.get_storage_policy_id_by_name"><code class="name flex">
<span>def <span class="ident">get_storage_policy_id_by_name</span></span>(<span>url, username, password, policy_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Get storage policy id by name and return information via json.</p>
<h2 id="arguments">Arguments</h2>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>policy_name = The name of the storage policy (i.e. "vSAN Default Storage Policy")</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def get_storage_policy_id_by_name(url,username,password,policy_name):
    &#34;&#34;&#34;
    Get storage policy id by name and return information via json.

    Arguments:


    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    policy_name = The name of the storage policy (i.e. &#34;vSAN Default Storage Policy&#34;)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/fabric-vsphere-storage-policies&#39;.format(api_url_base,policy_name)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            sp_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if sp_name == policy_name:
                print(&#34;Found vSphere Storage Polcy: &#34; + policy_name)
                sp_id = json_data[&#39;content&#39;][n][&#39;id&#39;]
                return sp_id
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For vSphere Storage Policy: &#34; + policy_name)
                break
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.get_storage_profile_by_name"><code class="name flex">
<span>def <span class="ident">get_storage_profile_by_name</span></span>(<span>url, username, password, storage_profile_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Get Storage Profile by Name and return json information</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>storage_profile_name = Storage Profile Name</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def get_storage_profile_by_name(url,username,password,storage_profile_name):
    &#34;&#34;&#34;
    Get Storage Profile by Name and return json information

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    storage_profile_name = Storage Profile Name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/storage-profiles&#39;.format(api_url_base,policy_name)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            sp_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if sp_name == storage_profile_name:
                print(&#34;Found Storage Profile: &#34; + storage_profile_name)
                sp_id = json_data[&#39;content&#39;][n]
                return sp_id
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For Storage Profile: &#34; + storage_profile_name)
                break
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.get_template_by_name"><code class="name flex">
<span>def <span class="ident">get_template_by_name</span></span>(<span>url, username, password, template_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Finds the cloud template by name and returns information via json</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA Admin user</p>
<p>password = vRA Admin password</p>
<p>template_name = Name of the cloud template to find</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def get_template_by_name(url,username,password,template_name):
    &#34;&#34;&#34;
    Finds the cloud template by name and returns information via json

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    template_name = Name of the cloud template to find
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}blueprint/api/blueprints&#39;.format(api_url_base)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            templt_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if templt_name == template_name:
                print(&#34;Found Cloud Template: &#34; + template_name)
                template_id = json_data[&#39;content&#39;][n]
                return template_id
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For Cloud Template: &#34; + template_name)
                break
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.get_token"><code class="name flex">
<span>def <span class="ident">get_token</span></span>(<span>url, username, password)</span>
</code></dt>
<dd>
<div class="desc"><p>Retrieve Session Token from vRealize Automation</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def get_token(url,username, password):
    &#34;&#34;&#34;
    Retrieve Session Token from vRealize Automation
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;}
    api_url = &#39;{0}csp/gateway/am/api/login?access_token&#39;.format(api_url_base)
    data =  {
              &#34;username&#34;: username,
              &#34;password&#34;: password
            }
    response = requests.post(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        key = json_data[&#39;access_token&#39;]
        return key
    else:
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.get_variable_by_name"><code class="name flex">
<span>def <span class="ident">get_variable_by_name</span></span>(<span>url, username, password, variable_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Get Storage Profile by Name and return json information</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>storage_profile_name = Storage Profile Name</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def get_variable_by_name(url,username,password,variable_name):
    &#34;&#34;&#34;
    Get Storage Profile by Name and return json information

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    storage_profile_name = Storage Profile Name
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}codestream/api/variables&#39;.format(api_url_base)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        var_links = json_data[&#39;links&#39;]
        for x in var_links:
            var_name = json_data[&#39;documents&#39;][x][&#39;name&#39;]
            if var_name == variable_name:
                print(&#34;Found variable: &#34; + variable_name)
                var_id = json_data[&#39;documents&#39;][x][&#39;id&#39;]
                return var_id
            else:
                print(&#34;Variable &#34; + variable_name + &#34; not found!&#34;)
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.get_vsphere_datastore_by_name"><code class="name flex">
<span>def <span class="ident">get_vsphere_datastore_by_name</span></span>(<span>url, username, password, datastore_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Get vsphere datastore by name and return information via json.</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>datastore_name = The name of the datastore (i.e.sc2c01vsan01)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def get_vsphere_datastore_by_name(url,username,password,datastore_name):
    &#34;&#34;&#34;
    Get vsphere datastore by name and return information via json.

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    datastore_name = The name of the datastore (i.e.sc2c01vsan01)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/fabric-vsphere-datastores&#39;.format(api_url_base,datastore_name)
    response = requests.get(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        n = 0
        end_n = json_data[&#39;totalElements&#39;]
        end_n = end_n - 1
        while True:
            ds_name = json_data[&#39;content&#39;][n][&#39;name&#39;]
            if ds_name == datastore_name:
                print(&#34;Found vSphere Datastore: &#34; + datastore_name)
                ds_id = json_data[&#39;content&#39;][n]
                return ds_id
                break
            elif n &lt; end_n:
                n = n + 1
            elif n &gt;= end_n:
                print(&#34;No Match Found For vSphere Datastore: &#34; + datastore_name)
                break
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.release_template_version"><code class="name flex">
<span>def <span class="ident">release_template_version</span></span>(<span>url, username, password, template_name, version)</span>
</code></dt>
<dd>
<div class="desc"><p>Releases a version of the cloud template to the Service Broker catalog</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA Admin user</p>
<p>password = vRA Admin password</p>
<p>template_name = Name of the cloud template to find</p>
<p>version = version for the template (i.e. 1.1)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def release_template_version(url,username,password,template_name,version):
    &#34;&#34;&#34;
    Releases a version of the cloud template to the Service Broker catalog

    Arguments:

    url = vRA FQDN

    username = vRA Admin user

    password = vRA Admin password

    template_name = Name of the cloud template to find

    version = version for the template (i.e. 1.1)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    template_json = get_template_by_name(url,username,password,template_name)
    template_id = template_json[&#39;id&#39;]
    api_url = &#39;{0}blueprint/api/blueprints/{1}/versions/{2}/actions/release&#39;.format(api_url_base,template_id,version)
    response = requests.post(api_url, headers=headers, verify=False)
    if response.status_code == 200:
        print(&#39;Successfully Released Version of Cloud Template to Catalog&#39;)
        return &#39;Successfully Released Version of Cloud Template to Catalog&#39;
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.remove_all_cz_from_project"><code class="name flex">
<span>def <span class="ident">remove_all_cz_from_project</span></span>(<span>url, username, password, projname)</span>
</code></dt>
<dd>
<div class="desc"><p>Removes all CLoud Zones from project</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>proj_name = Provide name of a Project which to remove all Cloud Zones</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def remove_all_cz_from_project(url,username,password,projname):
    &#34;&#34;&#34;
    Removes all CLoud Zones from project

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    proj_name = Provide name of a Project which to remove all Cloud Zones
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    proj_json = get_proj_by_name(url,username,password,projname)
    proj_id = proj_json[&#39;id&#39;]
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}project-service/api/projects/{1}&#39;.format(api_url_base,proj_id)
    data =  {
              &#34;zoneAssignmentConfigurations&#34;: []
            }
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#34;Removed ALL Cloud Zones from project: &#34; + projname)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.set_bas_url"><code class="name flex">
<span>def <span class="ident">set_bas_url</span></span>(<span>url)</span>
</code></dt>
<dd>
<div class="desc"></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def set_bas_url(url):
    api_url_base = &#34;https://&#34; + url + &#34;/&#34;
    return api_url_base</code></pre>
</details>
</dd>
<dt id="vra_module.tag_cloudzone"><code class="name flex">
<span>def <span class="ident">tag_cloudzone</span></span>(<span>url, username, password, czname, tag_key, tag_value)</span>
</code></dt>
<dd>
<div class="desc"><p>Tag Cloud Zone</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>czname = Cloud Zone Name</p>
<p>tag_key = Key for the tag (i.e. env:tag_value)</p>
<p>tag_value = Value for the tag (i.e. tag_key:vsphere)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def tag_cloudzone(url,username,password,czname,tag_key,tag_value):
    &#34;&#34;&#34;
    Tag Cloud Zone

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    czname = Cloud Zone Name

    tag_key = Key for the tag (i.e. env:tag_value)

    tag_value = Value for the tag (i.e. tag_key:vsphere)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    czid = get_czid_by_name(url,username,password,czname)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/zones/{1}&#39;.format(api_url_base,czid)
    data =  {
              &#34;name&#34;: czname,
              &#34;tags&#34;: [
                {
                  &#34;key&#34;: tag_key,
                  &#34;value&#34;: tag_value
                }
              ]
            }
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#39;Successfully Tagged Cloud Zone&#39;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.tag_fabric_network"><code class="name flex">
<span>def <span class="ident">tag_fabric_network</span></span>(<span>url, username, password, fabric_net_name, tag_key, tag_value)</span>
</code></dt>
<dd>
<div class="desc"><p>Tags a discovered network in vRA.</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>fabric_net_name = The name of the network that was discovered by vRA discover service (i.e.web-network)</p>
<p>tag_key = The key for the tag (i.e env:tag_value)</p>
<p>tag_value = Th value for the tag (i.e. tag_key:vsphere)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def tag_fabric_network(url,username,password,fabric_net_name,tag_key,tag_value):
    &#34;&#34;&#34;
    Tags a discovered network in vRA.

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    fabric_net_name = The name of the network that was discovered by vRA discover service (i.e.web-network)

    tag_key = The key for the tag (i.e env:tag_value)

    tag_value = Th value for the tag (i.e. tag_key:vsphere)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username, password)
    fab_net_json = get_fabric_network_by_name(url,username,password,fabric_net_name)
    fab_net_id = fab_net_json[&#39;id&#39;]
    try:
        current_tags = fab_net_json[&#39;tags&#39;]
        new_tag = {&#34;key&#34;: tag_key,&#34;value&#34;: tag_value}
        current_tags.append(new_tag)
        tags = current_tags
    except:
        print(&#34;Currently no tags assigned&#34;)
        tags = []
        new_tag = {&#34;key&#34;: tag_key,&#34;value&#34;: tag_value}
        tags.append(new_tag)
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/fabric-networks/{1}&#39;.format(api_url_base,fab_net_id)
    data = {
              &#34;tags&#34;: tags
            }
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        print(&#39;Successfully Tagged Fabric Network: &#39; + fabric_net_name)
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.update_cloud_flavor"><code class="name flex">
<span>def <span class="ident">update_cloud_flavor</span></span>(<span>url, username, password, flavor_name, mapping_name, cloud_instance_name)</span>
</code></dt>
<dd>
<div class="desc"><p>Update Cloud Flavor</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>flavor_name = Name of the Flavor Mapping (i.e. aws)</p>
<p>mapping_name = The name that displays in Cloud Assembly for the flavor (i.e.Small)</p>
<p>cloud_instance_name = The name if the instance type from the public cloud (i.e. t2.small)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def update_cloud_flavor(url,username,password,flavor_name,mapping_name,cloud_instance_name):
    &#34;&#34;&#34;
    Update Cloud Flavor

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    flavor_name = Name of the Flavor Mapping (i.e. aws)

    mapping_name = The name that displays in Cloud Assembly for the flavor (i.e.Small)

    cloud_instance_name = The name if the instance type from the public cloud (i.e. t2.small)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username,password)
    flav_json = get_flavor_by_name(url,username,password,flavor_name)
    flav_id = flav_json[&#39;id&#39;]
    current_flavors = flav_json[&#39;flavorMappings&#39;][&#39;mapping&#39;]
    a = json.dumps(current_flavors)
    a = a[1:-1]
    new_flavor =  {mapping_name:{&#34;name&#34;: cloud_instance_name}}
    b = json.dumps(new_flavor)
    b = b[1:-1]
    combined = a + &#34;,&#34; + b
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/flavor-profiles/{1}&#39;.format(api_url_base,flav_id)
    payload = &#34;{&#34; + &#39;&#34;&#39; + &#34;flavorMapping&#34; + &#39;&#34;&#39; + &#34;:&#34; &#34; {&#34;+ combined + &#34;}}&#34;
    data = json.loads(payload)
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#39;Successfully Updated Cloud Flavor&#39;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.update_image_mapping"><code class="name flex">
<span>def <span class="ident">update_image_mapping</span></span>(<span>url, username, password, profile_name, image_name, image_id)</span>
</code></dt>
<dd>
<div class="desc"><p>Updates an existing Image Mapping.</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>profile_name = The name of the image profile (i.e.vsphere-images)</p>
<p>image_name = The name of the image (i.e. Ubuntu)</p>
<p>image_id = name of the image instance (i.e. ami-03659409b9c7d0c5f or vsphere-ubuntu-template)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def update_image_mapping(url,username,password,profile_name,image_name,image_id):
    &#34;&#34;&#34;
    Updates an existing Image Mapping.

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    profile_name = The name of the image profile (i.e.vsphere-images)

    image_name = The name of the image (i.e. Ubuntu)

    image_id = name of the image instance (i.e. ami-03659409b9c7d0c5f or vsphere-ubuntu-template)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username,password)
    img_json = get_image_profile_by_name(url,username,password,profile_name)
    img_id = img_json[&#39;id&#39;]
    current_image = img_json[&#39;imageMappings&#39;][&#39;mapping&#39;]
    a = json.dumps(current_image)
    a = a[1:-1]
    new_image = {image_name: {&#34;name&#34;: image_id}}
    b = json.dumps(new_image)
    b = b[1:-1]
    combined = a + &#34;,&#34; + b
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/image-profiles/{1}&#39;.format(api_url_base,img_id)
    payload = &#34;{&#34; + &#39;&#34;&#39; + &#34;imageMapping&#34; + &#39;&#34;&#39; + &#34;:&#34; &#34; {&#34;+ combined + &#34;}}&#34;
    data = json.loads(payload)
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#39;Successfully Updated Image Mapping: &#39; + profile_name)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
<dt id="vra_module.update_vsphere_flavor"><code class="name flex">
<span>def <span class="ident">update_vsphere_flavor</span></span>(<span>url, username, password, flavor_name, mapping_name, cpu_count, mem_count)</span>
</code></dt>
<dd>
<div class="desc"><p>Update vSphere Flavor</p>
<p>Arguments:</p>
<p>url = vRA FQDN</p>
<p>username = vRA admin user</p>
<p>password = vRA Admin password</p>
<p>flavor_name = Name of the Flavor Mapping (i.e. vsphere)</p>
<p>mapping_name = The name that displays in Cloud Assembly for the flavor (i.e.Small)</p>
<p>cpu_count = number of CPUs assigned using this flavor (i.e. 2)</p>
<p>mem_count = amount of memory assigned using this flavor in GB (i.e. 4)</p></div>
<details class="source">
<summary>
<span>Expand source code</span>
</summary>
<pre><code class="python">def update_vsphere_flavor(url,username,password,flavor_name,mapping_name,cpu_count,mem_count):
    &#34;&#34;&#34;
    Update vSphere Flavor

    Arguments:

    url = vRA FQDN

    username = vRA admin user

    password = vRA Admin password

    flavor_name = Name of the Flavor Mapping (i.e. vsphere)

    mapping_name = The name that displays in Cloud Assembly for the flavor (i.e.Small)

    cpu_count = number of CPUs assigned using this flavor (i.e. 2)

    mem_count = amount of memory assigned using this flavor in GB (i.e. 4)
    &#34;&#34;&#34;
    api_url_base = set_bas_url(url)
    access_key = get_token(url,username,password)
    flav_json = get_flavor_by_name(url,username,password,flavor_name)
    flav_id = flav_json[&#39;id&#39;]
    current_flavors = flav_json[&#39;flavorMappings&#39;][&#39;mapping&#39;]
    a = json.dumps(current_flavors)
    a = a[1:-1]
    new_flavor = {mapping_name:{&#34;cpuCount&#34;: cpu_count,&#34;memoryInMB&#34;: mem_count}}
    b = json.dumps(new_flavor)
    b = b[1:-1]
    combined = a + &#34;,&#34; + b
    headers = {&#39;Content-Type&#39;: &#39;application/json&#39;,&#39;Authorization&#39;: &#39;Bearer {0}&#39;.format(access_key)}
    api_url = &#39;{0}iaas/api/flavor-profiles/{1}&#39;.format(api_url_base,flav_id)
    payload = &#34;{&#34; + &#39;&#34;&#39; + &#34;flavorMapping&#34; + &#39;&#34;&#39; + &#34;:&#34; &#34; {&#34;+ combined + &#34;}}&#34;
    data = json.loads(payload)
    response = requests.patch(api_url, headers=headers, data=json.dumps(data), verify=False)
    if response.status_code == 200:
        print(&#39;Successfully Updated vSphere Flavor&#39;)
        json_data = json.loads(response.content.decode(&#39;utf-8&#39;))
        return json_data
    else:
        print(response.status_code)
        return response.status_code</code></pre>
</details>
</dd>
</dl>
</section>
<section>
</section>
</article>
<nav id="sidebar">
<h1>Index</h1>
<div class="toc">
<ul>
<li><a href="#vrealize-automation-8x-module-for-salt">vRealize Automation 8.x Module for Salt</a></li>
</ul>
</div>
<ul id="index">
<li><h3><a href="#header-functions">Functions</a></h3>
<ul class="">
<li><code><a title="vra_module.add_admin_to_project" href="#vra_module.add_admin_to_project">add_admin_to_project</a></code></li>
<li><code><a title="vra_module.add_cloudzone_to_project" href="#vra_module.add_cloudzone_to_project">add_cloudzone_to_project</a></code></li>
<li><code><a title="vra_module.add_group_admin_to_project" href="#vra_module.add_group_admin_to_project">add_group_admin_to_project</a></code></li>
<li><code><a title="vra_module.add_group_member_to_project" href="#vra_module.add_group_member_to_project">add_group_member_to_project</a></code></li>
<li><code><a title="vra_module.add_member_to_project" href="#vra_module.add_member_to_project">add_member_to_project</a></code></li>
<li><code><a title="vra_module.add_network_to_profile" href="#vra_module.add_network_to_profile">add_network_to_profile</a></code></li>
<li><code><a title="vra_module.add_nsxt_network_to_profile" href="#vra_module.add_nsxt_network_to_profile">add_nsxt_network_to_profile</a></code></li>
<li><code><a title="vra_module.add_sec_group_vsphere_net_profile" href="#vra_module.add_sec_group_vsphere_net_profile">add_sec_group_vsphere_net_profile</a></code></li>
<li><code><a title="vra_module.config_ondemand_sec_groups_vsphere_network_profile" href="#vra_module.config_ondemand_sec_groups_vsphere_network_profile">config_ondemand_sec_groups_vsphere_network_profile</a></code></li>
<li><code><a title="vra_module.create_actions_content_source" href="#vra_module.create_actions_content_source">create_actions_content_source</a></code></li>
<li><code><a title="vra_module.create_ansible_oss_integration" href="#vra_module.create_ansible_oss_integration">create_ansible_oss_integration</a></code></li>
<li><code><a title="vra_module.create_ansibletower_integration" href="#vra_module.create_ansibletower_integration">create_ansibletower_integration</a></code></li>
<li><code><a title="vra_module.create_aws_ca" href="#vra_module.create_aws_ca">create_aws_ca</a></code></li>
<li><code><a title="vra_module.create_aws_storage_profile" href="#vra_module.create_aws_storage_profile">create_aws_storage_profile</a></code></li>
<li><code><a title="vra_module.create_azure_ca" href="#vra_module.create_azure_ca">create_azure_ca</a></code></li>
<li><code><a title="vra_module.create_azure_storage_profile" href="#vra_module.create_azure_storage_profile">create_azure_storage_profile</a></code></li>
<li><code><a title="vra_module.create_blueprint_content_source" href="#vra_module.create_blueprint_content_source">create_blueprint_content_source</a></code></li>
<li><code><a title="vra_module.create_cloud_flavor" href="#vra_module.create_cloud_flavor">create_cloud_flavor</a></code></li>
<li><code><a title="vra_module.create_cs_variable" href="#vra_module.create_cs_variable">create_cs_variable</a></code></li>
<li><code><a title="vra_module.create_github_saas_integration" href="#vra_module.create_github_saas_integration">create_github_saas_integration</a></code></li>
<li><code><a title="vra_module.create_image_mapping" href="#vra_module.create_image_mapping">create_image_mapping</a></code></li>
<li><code><a title="vra_module.create_network_profile" href="#vra_module.create_network_profile">create_network_profile</a></code></li>
<li><code><a title="vra_module.create_nsxt_ca" href="#vra_module.create_nsxt_ca">create_nsxt_ca</a></code></li>
<li><code><a title="vra_module.create_project" href="#vra_module.create_project">create_project</a></code></li>
<li><code><a title="vra_module.create_sb_content_source" href="#vra_module.create_sb_content_source">create_sb_content_source</a></code></li>
<li><code><a title="vra_module.create_template_version" href="#vra_module.create_template_version">create_template_version</a></code></li>
<li><code><a title="vra_module.create_vsphere_ca" href="#vra_module.create_vsphere_ca">create_vsphere_ca</a></code></li>
<li><code><a title="vra_module.create_vsphere_flavor" href="#vra_module.create_vsphere_flavor">create_vsphere_flavor</a></code></li>
<li><code><a title="vra_module.create_vsphere_storage_profile" href="#vra_module.create_vsphere_storage_profile">create_vsphere_storage_profile</a></code></li>
<li><code><a title="vra_module.delete_cloudaccount" href="#vra_module.delete_cloudaccount">delete_cloudaccount</a></code></li>
<li><code><a title="vra_module.delete_cloudzone" href="#vra_module.delete_cloudzone">delete_cloudzone</a></code></li>
<li><code><a title="vra_module.delete_flavor_mapping" href="#vra_module.delete_flavor_mapping">delete_flavor_mapping</a></code></li>
<li><code><a title="vra_module.delete_image_mapping" href="#vra_module.delete_image_mapping">delete_image_mapping</a></code></li>
<li><code><a title="vra_module.delete_integration_by_name" href="#vra_module.delete_integration_by_name">delete_integration_by_name</a></code></li>
<li><code><a title="vra_module.delete_netprofile" href="#vra_module.delete_netprofile">delete_netprofile</a></code></li>
<li><code><a title="vra_module.delete_project" href="#vra_module.delete_project">delete_project</a></code></li>
<li><code><a title="vra_module.delete_sb_content_source" href="#vra_module.delete_sb_content_source">delete_sb_content_source</a></code></li>
<li><code><a title="vra_module.delete_storage_profile" href="#vra_module.delete_storage_profile">delete_storage_profile</a></code></li>
<li><code><a title="vra_module.delete_template" href="#vra_module.delete_template">delete_template</a></code></li>
<li><code><a title="vra_module.delete_variable" href="#vra_module.delete_variable">delete_variable</a></code></li>
<li><code><a title="vra_module.disable_tf_on_project" href="#vra_module.disable_tf_on_project">disable_tf_on_project</a></code></li>
<li><code><a title="vra_module.enable_tf_on_project" href="#vra_module.enable_tf_on_project">enable_tf_on_project</a></code></li>
<li><code><a title="vra_module.extract_values" href="#vra_module.extract_values">extract_values</a></code></li>
<li><code><a title="vra_module.get_ca_by_name" href="#vra_module.get_ca_by_name">get_ca_by_name</a></code></li>
<li><code><a title="vra_module.get_cloud_acct_type" href="#vra_module.get_cloud_acct_type">get_cloud_acct_type</a></code></li>
<li><code><a title="vra_module.get_cloud_regionid_by_name" href="#vra_module.get_cloud_regionid_by_name">get_cloud_regionid_by_name</a></code></li>
<li><code><a title="vra_module.get_czid_by_name" href="#vra_module.get_czid_by_name">get_czid_by_name</a></code></li>
<li><code><a title="vra_module.get_fabric_network_by_name" href="#vra_module.get_fabric_network_by_name">get_fabric_network_by_name</a></code></li>
<li><code><a title="vra_module.get_flavor_by_name" href="#vra_module.get_flavor_by_name">get_flavor_by_name</a></code></li>
<li><code><a title="vra_module.get_image_profile_by_name" href="#vra_module.get_image_profile_by_name">get_image_profile_by_name</a></code></li>
<li><code><a title="vra_module.get_integration_by_name" href="#vra_module.get_integration_by_name">get_integration_by_name</a></code></li>
<li><code><a title="vra_module.get_netprofile_by_name" href="#vra_module.get_netprofile_by_name">get_netprofile_by_name</a></code></li>
<li><code><a title="vra_module.get_nsxt_fabric_network_by_name" href="#vra_module.get_nsxt_fabric_network_by_name">get_nsxt_fabric_network_by_name</a></code></li>
<li><code><a title="vra_module.get_nsxt_router_link_by_name" href="#vra_module.get_nsxt_router_link_by_name">get_nsxt_router_link_by_name</a></code></li>
<li><code><a title="vra_module.get_proj_by_name" href="#vra_module.get_proj_by_name">get_proj_by_name</a></code></li>
<li><code><a title="vra_module.get_sb_content_source_by_name" href="#vra_module.get_sb_content_source_by_name">get_sb_content_source_by_name</a></code></li>
<li><code><a title="vra_module.get_sec_group_by_name" href="#vra_module.get_sec_group_by_name">get_sec_group_by_name</a></code></li>
<li><code><a title="vra_module.get_storage_policy_id_by_name" href="#vra_module.get_storage_policy_id_by_name">get_storage_policy_id_by_name</a></code></li>
<li><code><a title="vra_module.get_storage_profile_by_name" href="#vra_module.get_storage_profile_by_name">get_storage_profile_by_name</a></code></li>
<li><code><a title="vra_module.get_template_by_name" href="#vra_module.get_template_by_name">get_template_by_name</a></code></li>
<li><code><a title="vra_module.get_token" href="#vra_module.get_token">get_token</a></code></li>
<li><code><a title="vra_module.get_variable_by_name" href="#vra_module.get_variable_by_name">get_variable_by_name</a></code></li>
<li><code><a title="vra_module.get_vsphere_datastore_by_name" href="#vra_module.get_vsphere_datastore_by_name">get_vsphere_datastore_by_name</a></code></li>
<li><code><a title="vra_module.release_template_version" href="#vra_module.release_template_version">release_template_version</a></code></li>
<li><code><a title="vra_module.remove_all_cz_from_project" href="#vra_module.remove_all_cz_from_project">remove_all_cz_from_project</a></code></li>
<li><code><a title="vra_module.set_bas_url" href="#vra_module.set_bas_url">set_bas_url</a></code></li>
<li><code><a title="vra_module.tag_cloudzone" href="#vra_module.tag_cloudzone">tag_cloudzone</a></code></li>
<li><code><a title="vra_module.tag_fabric_network" href="#vra_module.tag_fabric_network">tag_fabric_network</a></code></li>
<li><code><a title="vra_module.update_cloud_flavor" href="#vra_module.update_cloud_flavor">update_cloud_flavor</a></code></li>
<li><code><a title="vra_module.update_image_mapping" href="#vra_module.update_image_mapping">update_image_mapping</a></code></li>
<li><code><a title="vra_module.update_vsphere_flavor" href="#vra_module.update_vsphere_flavor">update_vsphere_flavor</a></code></li>
</ul>
</li>
</ul>
</nav>
</main>
<footer id="footer">
<p>Generated by <a href="https://pdoc3.github.io/pdoc"><cite>pdoc</cite> 0.9.2</a>.</p>
</footer>
</body>
</html>
