<img width="657" alt="스크린샷 2023-10-16 오후 1 55 44" src="https://github.com/mr-olympia-jay/team-project-trello/assets/130229450/d4de7e58-b607-4f2f-8a7a-f83455100310"><p align="center">
<a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest





<h1 align="center">ERD</h1>
<hr>
<p align="center">
<img width="657" alt="erd-team-project-trello" src="https://github.com/mr-olympia-jay/team-project-trello/assets/130229450/c9d7a45b-68ef-49c5-b7dd-cb04f9909832">
</p>

<hr>
<h1 align="center">API</h1>
<hr>
<ul>
<li>
<h4>User</h4>
<ul>
<li>
<p>POST '/users' - signup</p>
</li>
<li>
<p>POST '/users/login' - login</p>
</li>
<li>
<p>GET '/users' - get current user</p>
</li>
<li>
<p>PATCH '/users' - update current user</p>
</li>
<li>
<p>DELETE '/users' - delete current user</p>
</li>
<li>
<p>POST '/users/image' - upload user profile image</p>
</li>
<li>
<p>GET '/users/image' - get user profile image</p>
</li>
</ul>
</li>
<li>
<h4>Card</h4>
<ul>
<li>
<p>GET '/cards/:id' - get card detail</p>
</li>
<li>
<p>POST '/cards' - create card</p>
</li>
<li>
<p>PUT '/cards/:id' - update card</p>
</li>
<li>
<p>DELETE '/cards/:id' - delete card</p>
</li>
</ul>
</li>
<li>
<h4>Comment</h4>
<ul>
    <li>
        <p>GET '/comments/:cardId' - get all comments</p>
    </li>
    <li>
        <p>POST '/comments/:cardId' - create comment</p>
    </li>
    <li>
        <p>PUT 'comments/:commentId' - update comment</p>
    </li>
    <li>
        <p>DELETE 'comments/:commentId' - delete comment</p>
    </li>
</ul>
</li>
<li>
<h4>Board</h4>
<ul>
<li>
<p>GET '/boards/createdBoards' - get all created boards</p>
</li>
<li>
<p>POST '/boards' - create board</p>
</li>
<li>
<p>PUT '/boards/:boardId' - update board</p>
</li>
<li>
<p>DELETE '/boards/:boardId' - delete board</p>
</li>
<li>
<p>POST '/boards/invite/:boardId' - invite user</p>
</li>
<li>
<p>GET '/boards/invitedBoards' - get all invited boards</p>
</li>
<li>
<p>GET '/boards/detail/:id' - get board detail</p>
</li>
<li>
<p>DELETE '/boards/invitedBoards/:boardId' - delete invited board</p>
</li>
</ul>
</li>
<li>
<h4>Column</h4>
<ul>
<li>
<p>GET '/columns' - get all columns</p>
</li>
<li>
<p>GET '/columns/:id' - get column detail</p>
</li>
<li>
<p>POST '/columns' - create column</p>
</li>
<li>
<p>PUT '/columns/:id' - update column</p>
</li>
<li>
<p>DELETE '/columns/:id' - delete column</p>
</li>
</ul>
</li>
</ul>
