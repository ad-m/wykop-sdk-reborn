Fork biblioteki [wykop-sdk](https://github.com/p1c2u/wykop-sdk) w której
staram się poprawiać sdk wraz z (nie)udokumentowanymi zmianami w api
wykopu.

Lista zmian:

-   Usunięcie parametru `login` i `password` z metod logujących przez
    api (potrzebny jest jedynie account\_key)

-   Usunięcie klienta v1

-   rozdzielenie `named params` i `api params`

-   metody PM:

    -   Conversation

    -   SendMessage

-   medoty notifications:

    -   MarkAsRead

Stan implementacji metod api

### Addlink

|||
|--- |--- |
|Metoda API|Metoda SDK|
|Draft|:x:|
|Images|:x:|
|Add|:x:|

### Entries

|||
|--- |--- |
|Metoda API|Metoda SDK|
|Stream|`get_stream_entries`|
|Hot|`get_hot_entries`|
|Active|:x:|
|Observed|:x:|
|Entry|`get_entry`|
|Add|:x:|
|Edit|?:x:|
|VoteUp|:x:|
|VoteRemove|:x:|
|Upvoters|:x:|
|Delete|:x:|
|Comment|:x:|
|CommentAdd|:x:|
|CommentEdit|:x:|
|CommentDelete|:x:|
|CommentVoteUp|:x:|
|CommentVoteRemove|:x:|
|ObservedComments|:x:|
|Favorite|:x:|
|SurveyVote|:x:|
|CommentFavorite|:x:|

### Hits

|||
|--- |--- |
|Metoda API|Metoda SDK|
|Popular|`get_hits_popular`|
|Day|?|
|Week|?|
|Month|`get_hits_month`|
|Year|?|

### Links

|||
|--- |--- |
|Metoda API|Metoda SDK|
|Promoted|`get_links_promoted`|
|Upcoming|?|
|Observed|?|
|Link|?|
|VoteUp|?|
|VoteRemove|?|
|VoteDown|?|
|Upvoters|?|
|Downvoters|?|
|Top|?|
|Comments|?|
|CommentVoteUp|?|
|CommentVoteDown|?|
|CommentVoteCancel|?|
|CommentAdd|?|
|CommentEdit|?|
|CommentDelete|?|
|Comment|?|
|Related|?|
|RelatedAdd|?|
|RelatedVoteUp|?|
|RelatedVoteDown|?|
|Favorite|?|

### Login
|||
|--- |--- |
|Metoda API|Metoda SDK|
|Index|?|
|Connect|?|

### Mywykop

|||
|--- |--- |
|Metoda API|Metoda SDK|
|Index|?|
|Tags|?|
|Users|?|
|Entries|?|
|Links|?|

### Notifications

|||
|--- |--- |
|Metoda API|Metoda SDK|
|Index|?|
|Count|?|
|HashTags|`get_hashtags_notifications`|
|HashTagsCount|`get_hashtags_notifications_count`|
|Total|?|
|TotalCount|`get_notifications_count`|
|ReadAllNotifications|?|
|ReadDirectedNotifications|?|
|ReadHashTagsNotifications|?|
|MarkAsRead|`mark_notification_as_read`|

### PM

|||
|--- |--- |
|Metoda API|Metoda SDK|
|ConversationsList|`get_conversations_list`|
|Conversation|`get_conversation`|
|SendMessage|`send_message`|
|DeleteConversation|?|

### Profiles

|||
|--- |--- |
|Metoda API|Metoda SDK|
|Index|?|
|Actions|?|
|Added|?|
|Commented|?|
|Comments|?|
|Published|?|
|Entries|?|
|CommentedEntries|?|
|EntriesComments|?|
|Related|?|
|Followers|?|
|Followed|?|
|Badges|?|
|Digged|?|
|Buried|?|
|Rank|?|
|Observe|`observe_profile`|
|UnObserve|`unobserve_profile`|
|Block|`block_profile`|
|UnBlock|`unblock_profile`|
|AvailableColors|?|

### Search

|||
|--- |--- |
|Metoda API|Metoda SDK|
|Links|?|
|Entries|?|
|Profiles|?|

### Settings 

|||
|--- |--- |
|Metoda API|Metoda SDK|
|Profile|?|
|Avatar|?|
|Background|?|
|Password|?|
|ResetPassword|?|

### Suggest

|||
|--- |--- |
|Metoda API|Metoda SDK|
|Tags|?|
|Users|?|

### Tags

|||
|--- |--- |
|Metoda API|Metoda SDK|
|Index|?|
|Links|?|
|Entries|?|
|Observe|?|
|Unobserve|?|
|Notify|?|
|Dontnotify|?|
|Block|?|
|Unblock|?|

### Terms

|||
|--- |--- |
|Metoda API|Metoda SDK|
|Index|?|
|Confirm|?|
