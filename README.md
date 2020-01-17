Place for all the silly slack shit.

Could be fun to actually wire up tests around some scripting of this.


var assert = require('assert');
describe.only('Array', function() {
  console.log('NICO');

  describe('#indexOf()', function() {
    it('should return -1 when the value is not present', function() {
      assert.equal([1, 2, 3].indexOf(4), -1);
    });
  });
});
