# SopTest
<section data-ng-controller="CustomersController">
    <div class="page-header">
        <h1>New Customer</h1>
    </div>
    <div class="col-md-12">
        <form class="form-horizontal" data-ng-submit="create()" novalidate>
            <fieldset>
                <div class="form-group">
                    <label class="control-label" for="name">Name</label>
                    <div class="controls">
                        <input type="text" data-ng-model="name" id="name" class="form-control" placeholder="Name" required>
                    </div>
                </div>
                <div class="form-group">
                    <input type="submit" class="btn btn-default">
                </div>
				<div data-ng-show="error" class="text-danger">
					<strong data-ng-bind="error"></strong>
				</div>
            </fieldset>
        </form>
    </div>
</section>
