<template>
  <div id="app" class="small-container">
    <h1>Employees</h1>

    <employee-table :employees="employees" />
  </div>
</template>

<script>
import EmployeeTable from './components/EmployeeTable.vue';

export default {
  name: 'App',
  components: {
    EmployeeTable
  },
  data() {
    return {
      employees: [
        {
          id: 1,
          name: 'Richard Hendricks',
          email: 'richard@piedpiper.com',
        },
        {
          id: 2,
          name: 'Bertram Gilfoyle',
          email: 'gilfoyle@piedpiper.com',
        },
        {
          id: 3,
          name: 'Dinesh Chugtai',
          email: 'dinesh@piedpiper.com',
        },
        {
          id: 4,
          name: 'Leon Shimizu',
          email: 'leon@test.com',
        }
      ]
    }
  }
}
</script>

<style>

</style>
