# github-api-events

This project will store Github payload for different event types intercepted via a webhook pushing to https://mcfoggy-github-events.free.beeceptor.com

## Push event

### headers

````json
{
  "content-length": "7415",
  "accept": "*/*",
  "user-agent": "GitHub-Hookshot/903858c",
  "x-github-event": "push",
  "x-github-delivery": "ee3a5c6c-51ef-11e9-91d4-9ec080853ae7",
  "content-type": "application/json"
}
````

### content
````json
{
	"ref": "refs/heads/master",
	"before": "f42f6e7a95daed777b023010ce2723fa7f56a467",
	"after": "be42068a54defbbb573bb5738df5ff4a12f62181",
	"created": false,
	"deleted": false,
	"forced": false,
	"base_ref": null,
	"compare": "https://github.com/McFoggy/github-api-events/compare/f42f6e7a95da...be42068a54de",
	"commits": [{
			"id": "be42068a54defbbb573bb5738df5ff4a12f62181",
			"tree_id": "9e158213092dee321983123c1db5ec3e07b55a40",
			"distinct": true,
			"message": "switching to beeceptor.com",
			"timestamp": "2019-03-29T07:57:33+01:00",
			"url": "https://github.com/McFoggy/github-api-events/commit/be42068a54defbbb573bb5738df5ff4a12f62181",
			"author": {
				"name": "Matthieu Brouillard",
				"email": "matthieu@brouillard.fr",
				"username": "McFoggy"
			},
			"committer": {
				"name": "GitHub",
				"email": "noreply@github.com",
				"username": "web-flow"
			},
			"added": [],
			"removed": [],
			"modified": ["README.md"]
		}
	],
	"head_commit": {
		"id": "be42068a54defbbb573bb5738df5ff4a12f62181",
		"tree_id": "9e158213092dee321983123c1db5ec3e07b55a40",
		"distinct": true,
		"message": "switching to beeceptor.com",
		"timestamp": "2019-03-29T07:57:33+01:00",
		"url": "https://github.com/McFoggy/github-api-events/commit/be42068a54defbbb573bb5738df5ff4a12f62181",
		"author": {
			"name": "Matthieu Brouillard",
			"email": "matthieu@brouillard.fr",
			"username": "McFoggy"
		},
		"committer": {
			"name": "GitHub",
			"email": "noreply@github.com",
			"username": "web-flow"
		},
		"added": [],
		"removed": [],
		"modified": ["README.md"]
	},
	"repository": {
		"id": 178348886,
		"node_id": "MDEwOlJlcG9zaXRvcnkxNzgzNDg4ODY=",
		"name": "github-api-events",
		"full_name": "McFoggy/github-api-events",
		"private": false,
		"owner": {
			"name": "McFoggy",
			"email": "matthieu@brouillard.fr",
			"login": "McFoggy",
			"id": 1119660,
			"node_id": "MDQ6VXNlcjExMTk2NjA=",
			"avatar_url": "https://avatars2.githubusercontent.com/u/1119660?v=4",
			"gravatar_id": "",
			"url": "https://api.github.com/users/McFoggy",
			"html_url": "https://github.com/McFoggy",
			"followers_url": "https://api.github.com/users/McFoggy/followers",
			"following_url": "https://api.github.com/users/McFoggy/following{/other_user}",
			"gists_url": "https://api.github.com/users/McFoggy/gists{/gist_id}",
			"starred_url": "https://api.github.com/users/McFoggy/starred{/owner}{/repo}",
			"subscriptions_url": "https://api.github.com/users/McFoggy/subscriptions",
			"organizations_url": "https://api.github.com/users/McFoggy/orgs",
			"repos_url": "https://api.github.com/users/McFoggy/repos",
			"events_url": "https://api.github.com/users/McFoggy/events{/privacy}",
			"received_events_url": "https://api.github.com/users/McFoggy/received_events",
			"type": "User",
			"site_admin": false
		},
		"html_url": "https://github.com/McFoggy/github-api-events",
		"description": null,
		"fork": false,
		"url": "https://github.com/McFoggy/github-api-events",
		"forks_url": "https://api.github.com/repos/McFoggy/github-api-events/forks",
		"keys_url": "https://api.github.com/repos/McFoggy/github-api-events/keys{/key_id}",
		"collaborators_url": "https://api.github.com/repos/McFoggy/github-api-events/collaborators{/collaborator}",
		"teams_url": "https://api.github.com/repos/McFoggy/github-api-events/teams",
		"hooks_url": "https://api.github.com/repos/McFoggy/github-api-events/hooks",
		"issue_events_url": "https://api.github.com/repos/McFoggy/github-api-events/issues/events{/number}",
		"events_url": "https://api.github.com/repos/McFoggy/github-api-events/events",
		"assignees_url": "https://api.github.com/repos/McFoggy/github-api-events/assignees{/user}",
		"branches_url": "https://api.github.com/repos/McFoggy/github-api-events/branches{/branch}",
		"tags_url": "https://api.github.com/repos/McFoggy/github-api-events/tags",
		"blobs_url": "https://api.github.com/repos/McFoggy/github-api-events/git/blobs{/sha}",
		"git_tags_url": "https://api.github.com/repos/McFoggy/github-api-events/git/tags{/sha}",
		"git_refs_url": "https://api.github.com/repos/McFoggy/github-api-events/git/refs{/sha}",
		"trees_url": "https://api.github.com/repos/McFoggy/github-api-events/git/trees{/sha}",
		"statuses_url": "https://api.github.com/repos/McFoggy/github-api-events/statuses/{sha}",
		"languages_url": "https://api.github.com/repos/McFoggy/github-api-events/languages",
		"stargazers_url": "https://api.github.com/repos/McFoggy/github-api-events/stargazers",
		"contributors_url": "https://api.github.com/repos/McFoggy/github-api-events/contributors",
		"subscribers_url": "https://api.github.com/repos/McFoggy/github-api-events/subscribers",
		"subscription_url": "https://api.github.com/repos/McFoggy/github-api-events/subscription",
		"commits_url": "https://api.github.com/repos/McFoggy/github-api-events/commits{/sha}",
		"git_commits_url": "https://api.github.com/repos/McFoggy/github-api-events/git/commits{/sha}",
		"comments_url": "https://api.github.com/repos/McFoggy/github-api-events/comments{/number}",
		"issue_comment_url": "https://api.github.com/repos/McFoggy/github-api-events/issues/comments{/number}",
		"contents_url": "https://api.github.com/repos/McFoggy/github-api-events/contents/{+path}",
		"compare_url": "https://api.github.com/repos/McFoggy/github-api-events/compare/{base}...{head}",
		"merges_url": "https://api.github.com/repos/McFoggy/github-api-events/merges",
		"archive_url": "https://api.github.com/repos/McFoggy/github-api-events/{archive_format}{/ref}",
		"downloads_url": "https://api.github.com/repos/McFoggy/github-api-events/downloads",
		"issues_url": "https://api.github.com/repos/McFoggy/github-api-events/issues{/number}",
		"pulls_url": "https://api.github.com/repos/McFoggy/github-api-events/pulls{/number}",
		"milestones_url": "https://api.github.com/repos/McFoggy/github-api-events/milestones{/number}",
		"notifications_url": "https://api.github.com/repos/McFoggy/github-api-events/notifications{?since,all,participating}",
		"labels_url": "https://api.github.com/repos/McFoggy/github-api-events/labels{/name}",
		"releases_url": "https://api.github.com/repos/McFoggy/github-api-events/releases{/id}",
		"deployments_url": "https://api.github.com/repos/McFoggy/github-api-events/deployments",
		"created_at": 1553842131,
		"updated_at": "2019-03-29T06:54:43Z",
		"pushed_at": 1553842654,
		"git_url": "git://github.com/McFoggy/github-api-events.git",
		"ssh_url": "git@github.com:McFoggy/github-api-events.git",
		"clone_url": "https://github.com/McFoggy/github-api-events.git",
		"svn_url": "https://github.com/McFoggy/github-api-events",
		"homepage": null,
		"size": 0,
		"stargazers_count": 0,
		"watchers_count": 0,
		"language": null,
		"has_issues": true,
		"has_projects": true,
		"has_downloads": true,
		"has_wiki": true,
		"has_pages": false,
		"forks_count": 0,
		"mirror_url": null,
		"archived": false,
		"open_issues_count": 0,
		"license": null,
		"forks": 0,
		"open_issues": 0,
		"watchers": 0,
		"default_branch": "master",
		"stargazers": 0,
		"master_branch": "master"
	},
	"pusher": {
		"name": "McFoggy",
		"email": "matthieu@brouillard.fr"
	},
	"sender": {
		"login": "McFoggy",
		"id": 1119660,
		"node_id": "MDQ6VXNlcjExMTk2NjA=",
		"avatar_url": "https://avatars2.githubusercontent.com/u/1119660?v=4",
		"gravatar_id": "",
		"url": "https://api.github.com/users/McFoggy",
		"html_url": "https://github.com/McFoggy",
		"followers_url": "https://api.github.com/users/McFoggy/followers",
		"following_url": "https://api.github.com/users/McFoggy/following{/other_user}",
		"gists_url": "https://api.github.com/users/McFoggy/gists{/gist_id}",
		"starred_url": "https://api.github.com/users/McFoggy/starred{/owner}{/repo}",
		"subscriptions_url": "https://api.github.com/users/McFoggy/subscriptions",
		"organizations_url": "https://api.github.com/users/McFoggy/orgs",
		"repos_url": "https://api.github.com/users/McFoggy/repos",
		"events_url": "https://api.github.com/users/McFoggy/events{/privacy}",
		"received_events_url": "https://api.github.com/users/McFoggy/received_events",
		"type": "User",
		"site_admin": false
	}
}
````
