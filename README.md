# Core
Core of the E.coo.systems

#Parse Error

 proxy | time="2020-08-01T18:35:35Z" level=info msg="proxy starting" commit=417a8c750c4f47906f9fcc309451323d68ecc0d3
  proxy | 2020/08/01 18:35:35 Listening (:1080)
fetcher | yarn config v1.22.4
fetcher | success Set "cafile" to "/etc/ssl/certs/ca-certificates.crt".
fetcher | Done in 0.02s.
fetcher | INFO <job_42231946> Starting job processing
  proxy | 2020/08/01 18:35:39 GET https://api.github.com:443/repos/phibosGit/Core
  proxy | 2020/08/01 18:35:39 * authenticating github api request
  proxy | 2020/08/01 18:35:39 200 https://api.github.com:443/repos/phibosGit/Core
  proxy | 2020/08/01 18:35:39 GET https://api.github.com:443/repos/phibosGit/Core/git/refs/heads/master
  proxy | 2020/08/01 18:35:39 * authenticating github api request
  proxy | 2020/08/01 18:35:39 200 https://api.github.com:443/repos/phibosGit/Core/git/refs/heads/master
  proxy | 2020/08/01 18:35:39 GET https://api.github.com:443/repos/phibosGit/Core/contents/?ref=8a0c0cd57c5b6c0ece8b9644583a821486c29762
  proxy | 2020/08/01 18:35:39 * authenticating github api request
  proxy | 2020/08/01 18:35:39 200 https://api.github.com:443/repos/phibosGit/Core/contents/?ref=8a0c0cd57c5b6c0ece8b9644583a821486c29762
  proxy | 2020/08/01 18:35:39 GET https://api.github.com:443/repos/phibosGit/Core/contents/gems.rb?ref=8a0c0cd57c5b6c0ece8b9644583a821486c29762
  proxy | 2020/08/01 18:35:39 * authenticating github api request
  proxy | 2020/08/01 18:35:39 200 https://api.github.com:443/repos/phibosGit/Core/contents/gems.rb?ref=8a0c0cd57c5b6c0ece8b9644583a821486c29762
fetcher | (string):13:23: error: unexpected token tCOLON
fetcher | (string):13: gem "ronn", platform: :
fetcher | (string):13:                       ^
fetcher | ERROR <job_42231946> Error during file fetching; aborting
fetcher | INFO <job_42231946> Finished job processing
