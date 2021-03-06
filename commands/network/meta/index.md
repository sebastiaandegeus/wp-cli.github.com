---
layout: default
title: 'wp network meta'
display_global_parameters: true
---

<small>[Commands](/commands/) &raquo; [network](/commands/network/) &raquo; meta</small>

`wp network meta` - Manage network custom fields.

<small>Quick links: <a href="https://github.com/wp-cli/wp-cli/issues?q=is%3Aopen+label%3Acommand%3Anetwork-meta+sort%3Aupdated-desc">Github issues</a></small>

<hr />

### EXAMPLES

    # Get a list of super-admins
    $ wp network meta get 1 site_admins
    array (
      0 =&gt; 'supervisor',
    )





### SUBCOMMANDS

<table>
	<thead>
	<tr>
		<th>Name</th>
		<th>Description</th>
	</tr>
	</thead>
	<tbody>
		<tr>
			<td><a href="/commands/network/meta/add/">add</a></td>
			<td>Add a meta field.</td>
		</tr>
		<tr>
			<td><a href="/commands/network/meta/delete/">delete</a></td>
			<td>Delete a meta field.</td>
		</tr>
		<tr>
			<td><a href="/commands/network/meta/get/">get</a></td>
			<td>Get meta field value.</td>
		</tr>
		<tr>
			<td><a href="/commands/network/meta/list/">list</a></td>
			<td>List all metadata associated with an object.</td>
		</tr>
		<tr>
			<td><a href="/commands/network/meta/update/">update</a></td>
			<td>Update a meta field.</td>
		</tr>
	</tbody>
</table>
