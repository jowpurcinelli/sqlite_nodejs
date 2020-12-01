# sqlite_nodejs
Notes and useful stuff





<code>
  database.select(`SELECT COUNT(*) as count FROM record WHERE meetingId = ? AND recordId = ?`, [5, 8], (res) => {
  if(res[`count`]) {
    console.log(res[`count`])
  } else {
    console.log(`Error: ${res}`)
  }
})
  
  module.exports = {
  extends: 'kentcdodds',
  rules: {
    // your overrides
  },
}
</code> 
