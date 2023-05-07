# frozen_string_literal: true

# danger-lclを読み込み
# danger.import_dangerfile(github: "XXX/danger-lcl")

if github.pr_body.length < 5
  fail "Pull Request descriptionの記載をお願いします"
end

fail "reviewerを指定して下さい" if github.pr_json[:requested_reviewers].empty?
