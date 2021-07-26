<template>
  <div>
    <div class="row">
      <div class="col-md-12">
        <div class="card">
          <div class="card-header">
            <center><h1 slot="header" class="card-title">SOUVENIR</h1></center>
            <center><p class="category">
              Choose Your Favorite Souvenir
            </p></center>
          </div>
          <div class="card-body all-icons">
            <div class="row">
              <div
                class="font-icon-list col-lg-2 col-md-3 col-sm-4 col-xs-6 col-xs-6"
              >
                <div class="font-icon-detail">
                  <i class="tim-icons icon-alert-circle-exc"></i>
                  <p>icon-alert-circle-exc</p>
                </div>
              </div>
              <div
                class="font-icon-list col-lg-2 col-md-3 col-sm-4 col-xs-6 col-xs-6"
              >
                <div class="font-icon-detail">
                  <i class="tim-icons icon-align-center"></i>
                  <p>icon-align-center</p>
                </div>
              </div>
              <div
                class="font-icon-list col-lg-2 col-md-3 col-sm-4 col-xs-6 col-xs-6"
              >
                <div class="font-icon-detail">
                  <i class="tim-icons icon-align-left-2"></i>
                  <p>icon-align-left-2</p>
                </div>
              </div>
              <div
                class="font-icon-list col-lg-2 col-md-3 col-sm-4 col-xs-6 col-xs-6"
              >
                <div class="font-icon-detail">
                  <i class="tim-icons icon-app"></i>
                  <p>icon-app</p>
                </div>
              </div>
              <div
                class="font-icon-list col-lg-2 col-md-3 col-sm-4 col-xs-6 col-xs-6"
              >
                <div class="font-icon-detail">
                  <i class="tim-icons icon-atom"></i>
                  <p>icon-atom</p>
                </div>
              </div>
              <div
                class="font-icon-list col-lg-2 col-md-3 col-sm-4 col-xs-6 col-xs-6"
              >
                <div class="font-icon-detail">
                  <i class="tim-icons icon-attach-87"></i>
                  <p>icon-attach-87</p>
                </div>
              </div>
              <div
                class="font-icon-list col-lg-2 col-md-3 col-sm-4 col-xs-6 col-xs-6"
              >
                <div class="font-icon-detail">
                  <i class="tim-icons icon-badge"></i>
                  <p>icon-badge</p>
                </div>
              </div>
              <div
                class="font-icon-list col-lg-2 col-md-3 col-sm-4 col-xs-6 col-xs-6"
              >
                <div class="font-icon-detail">
                  <i class="tim-icons icon-bag-16"></i>
                  <p>icon-bag-16</p>
                </div>
              </div>
              <div
                class="font-icon-list col-lg-2 col-md-3 col-sm-4 col-xs-6 col-xs-6"
              >
                <div class="font-icon-detail">
                  <i class="tim-icons icon-bank"></i>
                  <p>icon-bank</p>
                </div>
              </div>
              <div
                class="font-icon-list col-lg-2 col-md-3 col-sm-4 col-xs-6 col-xs-6"
              >
                <div class="font-icon-detail">
                  <i class="tim-icons icon-basket-simple"></i>
                  <p>icon-basket-simple</p>
                </div>
              </div>
              <div
                class="font-icon-list col-lg-2 col-md-3 col-sm-4 col-xs-6 col-xs-6"
              >
                <div class="font-icon-detail">
                  <i class="tim-icons icon-bell-55"></i>
                  <p>icon-bell-55</p>
                </div>
              </div>
              <div
                class="font-icon-list col-lg-2 col-md-3 col-sm-4 col-xs-6 col-xs-6"
              >
                <div class="font-icon-detail">
                  <i class="tim-icons icon-bold"></i>
                  <p>icon-bold</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-md-12">
        <card card-body-classes="table-full-width">
          <h4 slot="header" class="card-title">Striped table</h4>
            <el-table :data="tableData">
            <el-table-column
              min-width="150"
              sortable
              label="Name"
              property="name"
            ></el-table-column>
            <el-table-column
              min-width="150"
              sortable
              label="Country"
              property="country"
            ></el-table-column>
            <el-table-column
              min-width="150"
              sortable
              label="City"
              property="city"
            ></el-table-column>
            <el-table-column
              min-width="150"
              sortable
              align="right"
              header-align="right"
              label="Salary"
              property="salary"
            ></el-table-column>
          </el-table>
        </card>
      </div>
      <div class="col-md-12">
        <card class="card-plain" body-classes="table-full-width">
          <template slot="header">
            <h4 class="card-title">Table on Plain Background</h4>
            <p class="category">Here is a subtitle for this table</p>
          </template>
          <el-table
            header-cell-class-name="table-transparent"
            header-row-class-name="table-transparent"
            row-class-name="table-transparent"
            :data="tableData"
          >
            <el-table-column
              min-width="150"
              sortable
              label="Name"
              property="name"
            ></el-table-column>
            <el-table-column
              min-width="150"
              sortable
              label="Country"
              property="country"
            ></el-table-column>
            <el-table-column
              min-width="150"
              sortable
              label="City"
              property="city"
            ></el-table-column>
            <el-table-column
              min-width="150"
              sortable
              align="right"
              header-align="right"
              label="Salary"
              property="salary"
            ></el-table-column>
          </el-table>
        </card>
      </div>
    </div>
  </div>

</template>
<script>
import { Table, TableColumn } from 'element-ui';

export default {
// name: 'icons'
 name: 'regular',
  components: {
    [Table.name]: Table,
    [TableColumn.name]: TableColumn
  },
  data() {
    return {
      tableData: [
        {
          id: 1,
          name: 'Dakota Rice',
          salary: '$36.738',
          country: 'Niger',
          city: 'Oud-Turnhout'
        },
        {
          id: 2,
          name: 'Minerva Hooper',
          salary: '$23,789',
          country: 'Curaçao',
          city: 'Sinaai-Waas'
        },
        {
          id: 3,
          name: 'Sage Rodriguez',
          salary: '$56,142',
          country: 'Netherlands',
          city: 'Baileux'
        },
        {
          id: 4,
          name: 'Philip Chaney',
          salary: '$38,735',
          country: 'Korea, South',
          city: 'Overland Park'
        },
        {
          id: 5,
          name: 'Doris Greene',
          salary: '$63,542',
          country: 'Malawi',
          city: 'Feldkirchen in Kärnten'
        }
      ]
    };
  }
};
</script>
<style>
.table-transparent {
  background-color: transparent !important;
}
</style>

