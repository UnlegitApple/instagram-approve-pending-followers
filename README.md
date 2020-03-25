# Instagram approve pending followers
Approve all pending followers ( for private accounts )

(I forked it because I reduced the (hardcoded) delay to 2 seconds)

Install this package globally:

    npm install https://github.com/UnlegitApple/instagram-approve-pending-followers -g

Once you have done that, you should be able to run the cli:

    approvePendingFollowers -u myusername -p 'mypassword'


It approves 200 requests in sequential order. It's on a continuous loop of 55minutes. So just leave it running on a machine somewhere and you'll never have to hit 'approve' again.
