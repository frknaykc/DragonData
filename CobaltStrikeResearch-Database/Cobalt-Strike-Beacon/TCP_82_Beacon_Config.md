
### x86 Configuration:
- **beacon_type:** HTTP
- **dns-beacon.strategy_fail_seconds:** -1
- **dns-beacon.strategy_fail_x:** -1
- **dns-beacon.strategy_rotate_seconds:** -1
- **http-get.client:**
  - Cookie
- **http-get.uri:** 176.32.35.104,/en_US/all.js
- **http-get.verb:** GET
- **http-post.client:**
  - Content-Type: application/octet-stream
  - id
- **http-post.uri:** /submit.php
- **http-post.verb:** POST
- **maxgetsize:** 1048576
- **port:** 82
- **post-ex.spawnto_x64:** %windir%\sysnative\rundll32.exe
- **post-ex.spawnto_x86:** %windir%\syswow64\rundll32.exe
- **process-inject.execute:**
  - CreateThread
  - SetThreadContext
  - CreateRemoteThread
  - RtlCreateUserThread
- **process-inject.startrwx:** 64
- **process-inject.stub:** 32cd41edf0810c5b5f498edf4731cc6d
- **process-inject.userwx:** 64
- **proxy.behavior:** 2 (Use IE settings)
- **server.publickey_md5:** e9ae865f5ce035176457188409f6020a
- **sleeptime:** 60000
- **useragent_header:** Mozilla/4.0 (compatible; MSIE 9.0; Windows NT 6.1; Trident/5.0)
- **uses_cookies:** 1

### x64 Configuration:
- **beacon_type:** HTTP
- **dns-beacon.strategy_fail_seconds:** -1
- **dns-beacon.strategy_fail_x:** -1
- **dns-beacon.strategy_rotate_seconds:** -1
- **http-get.client:**
  - Cookie
- **http-get.uri:** 176.32.35.104,/cx
- **http-get.verb:** GET
- **http-post.client:**
  - Content-Type: application/octet-stream
  - id
- **http-post.uri:** /submit.php
- **http-post.verb:** POST
- **maxgetsize:** 1048576
- **port:** 82
- **post-ex.spawnto_x64:** %windir%\sysnative\rundll32.exe
- **post-ex.spawnto_x86:** %windir%\syswow64\rundll32.exe
- **process-inject.execute:**
  - CreateThread
  - SetThreadContext
  - CreateRemoteThread
  - RtlCreateUserThread
- **process-inject.startrwx:** 64
- **process-inject.stub:** 32cd41edf0810c5b5f498edf4731cc6d
- **process-inject.userwx:** 64
- **proxy.behavior:** 2 (Use IE settings)
- **server.publickey_md5:** e9ae865f5ce035176457188409f6020a
- **sleeptime:** 60000
- **useragent_header:** Mozilla/4.0 (compatible; MSIE 8.0; Windows NT 5.1; Trident/4.0; .NET4.0C; .NET4.0E)
- **uses_cookies:** 1
