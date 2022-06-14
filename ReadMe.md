<h1 align="center">Hi Everyone</h1>

<p align="center">
  <b>🖤 Simple script to delete all your friends requests 🖤</b><br>
  <br><br>
  <img src="https://cdn.discordapp.com/attachments/762750100500906044/860549000939831316/183296.gif">
    <br><br>
  <b>🖤 Past the code in the consol when you are in the Friends request tabs ( if you are on friends tab, it gonna delete it) 🖤</b><br>
</p>

```var friends = (webpackChunkdiscord_app.push([
    [''], {},
    e => {
        m = [];
        for (let c in e.c) m.push(e.c[c])
    }
]), m).find(m => m?.exports?.default?.removeRelationship !== void 0).exports.default

function removeFriendsAll() {
    var pendingPage = document.getElementsByClassName('content-2a4AW9')[1],
    allPendingOnCurrentScreen = document.getElementsByClassName('peopleListItem-u6dGxF');
    if (allPendingOnCurrentScreen.length != 0) {
        for (var pendingFriend of allPendingOnCurrentScreen) {
                var friendID = pendingFriend.getAttribute('data-list-item-id');
                friendID = friendID.replace('people-list___', '');
                friends.removeRelationship(friendID, {location: "Friends"})
                console.log('Removed:', friendID);
        }
        setTimeout(removeFriendsAll, 5000);
    }
}
removeFriendsAll();```
