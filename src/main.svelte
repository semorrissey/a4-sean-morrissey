
    <div class="container" id="app" style="display: none;">
      <div class="flex-container">
        <h1 onclick="location.reload()">
          Project Manager
        </h1>
        <p>
          A WebApp for managing projects. All priorities are determined by time
          frame.
        </p>
        <h2>
          Submit a Project Here:
        </h2>
        <form style="display: flex;
  flex-direction: row;
  align-items: center;">
          <input
            type="text"
            id="pName"
            onfocus="this.value = ''"
            placeholder="Project Name"
          />
          <input
            type="text"
            id="pDesc"
            onfocus="this.value = ''"
            placeholder="Project Description"
          />
          <input
            type="text"
            id="pSDate"
            onfocus="this.value = ''"
            placeholder="Start Date MM-DD-YYYY"
          />
          <input
            type="text"
            id="pEDate"
            onfocus="this.value = ''"
            placeholder="End Date MM-DD-YYYY"
          />
          <button id="submit">Submit</button>
        </form>
        <p id="status"></p>

        <h2>
          Current Projects
        </h2>
        <button id="reset">
          Reset
        </button>
        <p>
          *Resets the table in the database
        </p>
        <button id="example">
          Add an Example
        </button>
        <p>
          *Adds an example entry
        </p>
        <table id="projectTable" class="table">
          <tr>
            <th>Name</th>
            <th>Description</th>
            <th>Start Date</th>
            <th>End Date</th>
            <th>Priority</th>
            <th>Edit</th>
          </tr>
        </table>
      </div>
    </div>