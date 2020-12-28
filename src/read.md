there is a error called (text is undefined) , everything going great .

go to components/todolist line 15..

( {todos.map((todo) => (
                    <Todo 
                        setTodos={setTodos}
                        todos={todos}    
                        todo={todo}
                        key={todo.id}
                        text={todo.text} // here
                    />)

this is the bug