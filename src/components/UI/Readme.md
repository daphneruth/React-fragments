# Fragments
- its an empty wrapper component
- does not render any real HTML elements to the DOM but fulfils React/JSX requirment

  - example:
      <React.Fragment>
      <AddUser onAddUser={addUserHandler} />
      <UsersList users={usersList} />
    </React.Fragment>
  

