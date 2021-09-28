
# Install the divercity ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_divercity

# Clone the divercity ansible role. 
git clone git@github.com:computate-org/computate_divercity.git ~/.ansible/roles/computate.computate_divercity
```

# Run the divercity ansible playbook to install divercity locally (requires sudo privileges with -K). 

```bash
cd ~/.ansible/roles/computate.computate_divercity
ansible-playbook -K install.yml
```

