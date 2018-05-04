## Tree View

Tree View


## Step 1:
  Create Doctype (Make sure doctype Non-Custom? )
  
## Step 2:

  frappe.ui.form.on('Tree', {
	refresh: function(frm) {

    }
  });
  
# Step 3:

class Tree(NestedSet):
	nsm_parent_field = 'parent_tree'
 


#### License

GPL v3
