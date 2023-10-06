# REACT WAREHOUSE PROJECT:-

To complete this project, we can follow these steps:

1. Set up the project:
   - Create a new React or Vue project using create-react-app or vue-cli.
   - Install the necessary dependencies like react-router-dom, redux, react-redux, or vue-router, vuex.

2. We have to create the necessary components:
   - WarehouseList: This component will display the list of warehouses.
   - WarehouseDetails: This component will display the details of a selected warehouse.
   - SearchBar: This component will allow users to search warehouses by name.
   - FilterBar: This component will allow users to filter warehouses based on city, cluster, and space available limit.

3. We have to implement the functionality:
   - Fetch the warehouse data from the provided JSON file and store it in the Redux store.
   - Implement the search functionality by filtering the warehouses based on the search input.
   - Implement the filter functionality by filtering the warehouses based on the selected filter options.
   - Implement the edit functionality by allowing users to edit the warehouse information.
   - Implement the add custom fields functionality by allowing users to add custom fields to a warehouse.

4. we have to style the components:
   - Use CSS to style the components according to the given layout.

5. Set up routing:
   - Use react-router-dom or vue-router to set up routing between the WarehouseList and WarehouseDetails components.


In this implementation, we use the useDispatch and useSelector hooks from react-redux to dispatch the fetchWarehouses action and select the warehouses from the Redux store. The useEffect hook is used to dispatch the action when the component mounts.
