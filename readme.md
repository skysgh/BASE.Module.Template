# About #

This is a repo template for creating BASE Modules.

Key aspects to notice:

* Module and relevant file names contain a `KWMODULENAME` token for quick renaming using the provided `post-build.ps1` script.
* Module is composed of multiple Assemblies, following DDD patterns, approximately as follows:
  * `*.Interface.UI.Web` invokes APIs found in
  * `*.Interface.API.REST`, composed of thin Controllers wrapping
  * `*.Application` services that orchestrate calls between
  * `*.Domain`
  * `*.Infrastructure` and
  * `*.Substrate` referring to base contracts, etc.
 

