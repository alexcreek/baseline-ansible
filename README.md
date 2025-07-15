# baseline-ansible

## Usage

```
# Run an individual command
uv run ansible -i IP, all -m ping

# Run a playbook
uv run ansible-playbook playbook.yml -i IP,

# Run a playbook as a user
uv run ansible-playbook playbook.yml -i IP, -u username -b
```
