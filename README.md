# Reactjs_for_beginners

**** React Js Basic Command
1. npx crate-react-app firstapp
2. cd firstapp
3. npm start
4. import ReactDom from 'react-dom';
ReactDom.render(
    <>
        <h1>Basant Mallick</h1>
        <h2>Hemant</h2>
    </>
        ,document.getElementById('root')
);




// import Header from './components/Header';

// import Content from './components/Content';

// import Footer from './components/Footer';


5. Install React Router

	npm install react-router-dom


6. For Page Without Refresh

	<Router>


            <Link to="/">Home</Link> &nbsp;
            <Link to="/about">About</Link>



                <Switch>
                    <Route path="/" component={Home} exact></Route>
                    <Route path="/about" component={About}></Route>
                </Switch>
            
            
            </Router>
